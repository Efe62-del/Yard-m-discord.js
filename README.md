const Discord = require('discord.js');
const client = new Discord.Client();
const ayarlar = require('./ayarlar.json');

var prefix = ayarlar.prefix;

client.on('ready', () => {
  console.log(`${client.user.tag}Oynamaya Hazır!`);
});
client.on('message', msg => {
  if (msg.content === 'Nerve') {
    msg.channel.sendMessage('Sizi dinliyorum!');
  }
  if (msg.content === 'nerve') {
    msg.reply('Sizi dinliyorum!');
  }
  if (msg.content === 'NERVE') {
    msg.reply('Sizi dinliyorum!');
  }
  if (msg.content === 'nERVE') {
    msg.reply('Sizi dinliyorum!');
  }
  if (msg.content === 'NervE') {
    msg.reply('Sizi dinliyorum!');
  }
  if (msg.content === 'NErve') {
    msg.reply('Sizi dinliyorum!');
  }
  if (msg.content === 'nerVE') {
    msg.reply('Sizi dinliyorum!');
  }
  if (msg.content === 'nervE') {
    msg.reply('Sizi dinliyorum!');
  }
  if (msg.content === 'NERVe') {
    msg.reply('Sizi dinliyorum!');
  }
  if (msg.content === 'NErVE') {
    msg.reply('Sizi dinliyorum!');
  }
  if (msg.content === 'nErVe') {
    msg.reply('Sizi dinliyorum!');
  }
  if (msg.content === 'NERve') {
    msg.reply('Sizi dinliyorum!');
  }
  if (msg.content === 'nERVE') {
    msg.reply('Sizi dinliyorum!');
  }
  if (!msg.content.startsWith(prefix)) {
     return;
}
if (msg.content === prefix + 'Oyun' ) {
  msg.reply('Nerve bir oyundur eğlence amaçlı yaratılmıştır ve hizmete sunulmuştur :)')
}
if (msg.content === prefix + 'oYuN' ) {
  msg.reply('Nerve bir oyundur eğlence amaçlı yaratılmıştır ve hizmete sunulmuştur :)')
}
if (msg.content === prefix + 'OyUN' ) {
  msg.reply('Nerve bir oyundur eğlence amaçlı yaratılmıştır ve hizmete sunulmuştur :)')
}
if (msg.content === prefix + 'oyUN' ) {
  msg.reply('Nerve bir oyundur eğlence amaçlı yaratılmıştır ve hizmete sunulmuştur :)')
}
if (msg.content === prefix + 'OYUn' ) {
  msg.reply('Nerve bir oyundur eğlence amaçlı yaratılmıştır ve hizmete sunulmuştur :)')
}
if (msg.content === prefix + 'OYun' ) {
  msg.reply('Nerve bir oyundur eğlence amaçlı yaratılmıştır ve hizmete sunulmuştur :)')
}
if (msg.content === prefix + 'oyun' ) {
  msg.reply('Nerve bir oyundur eğlence amaçlı yaratılmıştır ve hizmete sunulmuştur :)')
}
if (msg.content === prefix + 'oYUN' ) {
  msg.reply('Nerve bir oyundur eğlence amaçlı yaratılmıştır ve hizmete sunulmuştur :)')
}
if (msg.content === prefix + 'OYun' ) {
  msg.reply('Nerve bir oyundur eğlence amaçlı yaratılmıştır ve hizmete sunulmuştur :)')
}
if (msg.content === prefix + 'OYUN' ) {
  msg.reply('Nerve bir oyundur eğlence amaçlı yaratılmıştır ve hizmete sunulmuştur :)')
}
});
client.on('guildBanAdd' , (guild, user) => {
  let aramızakatılanlar = sendMessage.guild.channels.find('name', 'aramıza-katılanlar');
  if (!aramızakatılanlar) return;
  aramızakatılanlar.send('https://media.giphy.com/media/8njotXALXXNrW/giphy.gif **Adalet dağıtma zamanı gelmiş!** '+ user.username +'**Bakıyorum da suç işlemiş,Yargı dağıtmaya devam** :fist: :writing_hand:  :spy:' );
});
client.login('XXX);


