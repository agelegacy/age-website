import React, { useState } from "react";
import { motion } from "framer-motion";
import { Button } from "@/components/ui/button";

export default function AGEVetrina() {
  const [showDetails, setShowDetails] = useState(false);

  return (
    <div className="min-h-screen bg-cover bg-center text-white flex flex-col items-center p-10" style={{ backgroundImage: 'url(/mnt/data/A_high-tech_cybernetic_network_with_glowing_blue_a.png)' }}>
      {!showDetails ? (
        <>
          <motion.h1 
            className="text-5xl font-bold text-center mb-6 bg-gradient-to-r from-blue-400 to-purple-600 text-transparent bg-clip-text"
            initial={{ opacity: 0, y: -50 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 1 }}
          >
            AGE - Archivio Genetico Ereditario
          </motion.h1>
          
          <motion.p 
            className="text-lg text-gray-300 max-w-3xl text-center mb-6 bg-black bg-opacity-50 p-4 rounded-lg"
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            transition={{ delay: 0.5, duration: 1 }}
          >
            AGE rivoluziona il modo in cui lasciamo la nostra eredità digitale. 
            Collegando il DNA all'eredità, permette ai discendenti di accedere 
            a messaggi, immagini e informazioni cruciali, garantendo la continuità 
            della memoria familiare e la consapevolezza genetica.
          </motion.p>
          
          <motion.div 
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            transition={{ delay: 1, duration: 1 }}
          >
            <Button className="bg-blue-600 hover:bg-blue-800 text-white text-lg px-6 py-3 rounded-xl shadow-lg" onClick={() => setShowDetails(true)}>
              Scopri di più
            </Button>
          </motion.div>
        </>
      ) : (
        <motion.div 
          className="max-w-3xl text-center bg-black bg-opacity-50 p-6 rounded-lg"
          initial={{ opacity: 0 }}
          animate={{ opacity: 1 }}
          transition={{ duration: 1 }}
        >
          <h2 className="text-4xl font-bold mb-4">AGE - Il Futuro della Memoria Umana</h2>
          <p className="text-lg text-gray-300 mb-4">
            AGE, una piattaforma che unisce DNA, intelligenza artificiale ed eredità digitale, 
            permettendo alle persone di tramandare la propria memoria alle generazioni future.
          </p>
          <h3 className="text-2xl font-semibold mb-2">🧬 Il Problema che Risolve</h3>
          <p className="text-gray-300 mb-4">
            Oggi, dopo poche generazioni, la memoria familiare si perde. Non esiste un sistema sicuro per trasmettere ricordi digitali e informazioni sanitarie ai discendenti. AGE combina genealogia, IA e DNA in un’unica piattaforma.
          </p>
          <h3 className="text-2xl font-semibold mb-2">🧬 Come Funziona AGE?</h3>
          <ul className="text-gray-300 text-left mx-auto max-w-lg mb-4">
            <li><strong>1️⃣ Creazione del Profilo e Archivio Digitale:</strong> Foto, video, lettere digitali e documenti salvati in un cloud sicuro.</li>
            <li><strong>2️⃣ DNA e Accesso Ereditario:</strong> Solo i discendenti diretti possono accedere ai dati grazie all’analisi del DNA.</li>
            <li><strong>3️⃣ Albero Genealogico Interattivo:</strong> Connette i membri della famiglia con dati storici e genetici.</li>
            <li><strong>4️⃣ Archivio Medico Familiare:</strong> Traccia malattie ereditarie per la prevenzione sanitaria.</li>
            <li><strong>5️⃣ Intelligenza Artificiale Ereditabile:</strong> Una IA che simula la personalità dell’utente per interagire con i discendenti.</li>
            <li><strong>6️⃣ Testamento Digitale e Messaggi Post-Mortem:</strong> Lettere e video sbloccabili solo dopo la morte.</li>
            <li><strong>7️⃣ Archivio Multimediale Sicuro:</strong> Dati crittografati conservati in cloud decentralizzati.</li>
          </ul>
          <h3 className="text-2xl font-semibold mb-2">🧬 Perché AGE può Diventare un Colosso?</h3>
          <p className="text-gray-300 mb-6">
            ✅ Mercato in crescita: genealogia e IA supereranno i $100 miliardi nei prossimi 10 anni.<br/>
            ✅ Nessun competitor unisce DNA, IA ed eredità digitale in un unico ecosistema.<br/>
            ✅ Domanda crescente per la conservazione della memoria digitale.<br/>
            ✅ Modello di business scalabile e globale.
          </p>
          <Button className="bg-red-600 hover:bg-red-800 text-white text-lg px-6 py-3 rounded-xl shadow-lg" onClick={() => setShowDetails(false)}>
            Torna Indietro
          </Button>
        </motion.div>
      )}
    </div>
  );
}
