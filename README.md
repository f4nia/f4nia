exports.menu = (pushname, sender, prefix, banChats, ucapanWaktu, timeWib, timeWit, timeWita) => {
return`*╭─❒ 「 X - Dev Bot 」 ──────*
*│*
*│*⬡ *${ucapanWaktu} kak*
*│*⬡ *Nama : ${pushname}*
*│*⬡ *Tag     :* @${sender.split('@')[0]}
*│*⬡ *WIB    : ${timeWib}*
*│*⬡ *WIT    : ${timeWit}*
*│*⬡ *WITA  : ${timeWita}*
*│*⬡ *Prefix : 「 MULTI PREFIX 」*
*│*⬡ *Bot mode : ${banChats ? "SELF-MODE" : "PUBLIC-MODE"}*
*└───────────────────*
