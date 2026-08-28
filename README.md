# vanta-client
made by the same spanish kids that pasted mujina ( hero client ) and they are selling their new vibecoded paste to scam ppl out of their money w lies and they are stealing private info from their customers, they also banned me before i joined the server to prevent me spreading facts LOL , webhook -> https://discordapp.com/api/webhooks/1507223692831359117/ZeUOS52aOdwMP3d-OpQ7AAaS3a69U713SqBE_iRAtsl9
<img width="624" height="216" alt="image" src="https://github.com/user-attachments/assets/d76c543d-6cf5-4e0c-a816-7ceefbcd451d" />

# how to get the dll
by going to the https://notrash.lol/api/download_dll.php and running this script in the console
fetch('/api/download_dll.php', {
    headers: { 'Authorization': 'Bearer ' + (localStorage.getItem('vanta_token') || sessionStorage.getItem('vanta_token')) }
})
.then(r => {
    console.log('Durum:', r.status);
    console.log('Başlıklar:', r.headers);
    return r.blob();
})
.then(blob => {
    const a = document.createElement('a');
    a.href = URL.createObjectURL(blob);
    a.download = 'vanta.dll';
    a.click();
})
.catch(e => console.error('Hata:', e));

# vibecode proofs
<img width="481" height="165" alt="image" src="https://github.com/user-attachments/assets/8a1872cd-7127-495b-81b1-2a4586edd614" />
<img width="658" height="1090" alt="image" src="https://github.com/user-attachments/assets/74df9e98-e25b-4441-b12a-2e596f05f0ae" />

# stealer proofs
<img width="755" height="1284" alt="image" src="https://github.com/user-attachments/assets/b58599d8-5945-4767-8f3d-93cdf9cf31fa" />
