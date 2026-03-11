/**
 * @license
 * SPDX-License-Identifier: Apache-2.0
 */

import React from 'react';
import { motion } from 'motion/react';
import { Hammer, Wrench, MessageCircle, Clock, Calendar } from 'lucide-react';

export default function App() {
  const whatsappChannelUrl = "https://whatsapp.com/channel/0029VbAvDSX0QeahEg4kkE3U";

  return (
    <div className="min-h-screen bg-[#0a0a0a] text-white flex flex-col items-center justify-center p-6 relative overflow-hidden font-sans">
      {/* Atmospheric background elements */}
      <div className="absolute top-[-10%] left-[-10%] w-[40%] h-[40%] bg-emerald-500/10 blur-[120px] rounded-full" />
      <div className="absolute bottom-[-10%] right-[-10%] w-[40%] h-[40%] bg-blue-500/10 blur-[120px] rounded-full" />

      <motion.div 
        initial={{ opacity: 0, y: 20 }}
        animate={{ opacity: 1, y: 0 }}
        transition={{ duration: 0.8, ease: "easeOut" }}
        className="max-w-2xl w-full z-10 text-center"
      >
        {/* Icon Section */}
        <div className="flex justify-center mb-8 relative">
          <motion.div
            animate={{ 
              rotate: [0, 10, 0, -10, 0],
              y: [0, -5, 0]
            }}
            transition={{ 
              duration: 4, 
              repeat: Infinity,
              ease: "easeInOut"
            }}
            className="bg-emerald-500/10 p-6 rounded-3xl border border-emerald-500/20 backdrop-blur-sm"
          >
            <Hammer className="w-12 h-12 text-emerald-400" />
          </motion.div>
          <motion.div
            animate={{ 
              rotate: [0, -15, 0, 15, 0],
              x: [0, 5, 0]
            }}
            transition={{ 
              duration: 5, 
              repeat: Infinity,
              ease: "easeInOut",
              delay: 0.5
            }}
            className="absolute -top-4 -right-4 bg-blue-500/10 p-3 rounded-2xl border border-blue-500/20 backdrop-blur-sm"
          >
            <Wrench className="w-6 h-6 text-blue-400" />
          </motion.div>
        </div>

        {/* Main Text */}
        <h1 className="text-4xl md:text-6xl font-bold tracking-tight mb-4 bg-clip-text text-transparent bg-gradient-to-b from-white to-white/60">
          Website Under Maintenance
        </h1>
        
        <p className="text-lg md:text-xl text-zinc-400 mb-12 max-w-lg mx-auto leading-relaxed">
          We're currently upgrading our systems to provide you with a better experience. 
          We'll be back online in approximately <span className="text-emerald-400 font-semibold">two days</span>.
        </p>

        {/* Info Cards */}
        <div className="grid grid-cols-1 md:grid-cols-2 gap-4 mb-12">
          <div className="bg-white/5 border border-white/10 p-4 rounded-2xl flex items-center gap-4 text-left">
            <div className="bg-emerald-500/20 p-2 rounded-lg">
              <Clock className="w-5 h-5 text-emerald-400" />
            </div>
            <div>
              <p className="text-xs text-zinc-500 uppercase tracking-wider font-semibold">Status</p>
              <p className="text-sm text-zinc-200">System Upgrading</p>
            </div>
          </div>
          <div className="bg-white/5 border border-white/10 p-4 rounded-2xl flex items-center gap-4 text-left">
            <div className="bg-blue-500/20 p-2 rounded-lg">
              <Calendar className="w-5 h-5 text-blue-400" />
            </div>
            <div>
              <p className="text-xs text-zinc-500 uppercase tracking-wider font-semibold">Estimated Back</p>
              <p className="text-sm text-zinc-200">In 48 Hours</p>
            </div>
          </div>
        </div>

        {/* Action Button */}
        <div className="flex flex-col items-center gap-4">
          <motion.a
            href={whatsappChannelUrl}
            target="_blank"
            rel="noopener noreferrer"
            whileHover={{ scale: 1.02 }}
            whileTap={{ scale: 0.98 }}
            className="group relative inline-flex items-center justify-center gap-3 bg-[#25D366] hover:bg-[#20ba5a] text-black font-bold py-4 px-8 rounded-2xl transition-all shadow-[0_0_20px_rgba(37,211,102,0.3)] hover:shadow-[0_0_30px_rgba(37,211,102,0.5)]"
          >
            <MessageCircle className="w-6 h-6" />
            <span>Join WhatsApp Channel</span>
          </motion.a>
          <p className="text-sm text-zinc-500">
            Stay updated with our latest announcements
          </p>
        </div>
      </motion.div>

      {/* Footer */}
      <footer className="absolute bottom-8 text-zinc-600 text-xs tracking-widest uppercase">
        &copy; {new Date().getFullYear()} All Rights Reserved
      </footer>
    </div>
  );
}
