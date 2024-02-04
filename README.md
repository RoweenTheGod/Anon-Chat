### Anon-Chat ###

Welcome to the Chat App! This secure and encrypted chat application is built using Node.js, Express, and Socket.io. It ensures your messages remain private through Advanced Encryption Standard (AES) and Rivest-Shamir-Adleman (RSA) encryption. Follow the steps below to set up the chat app and enjoy secure communication with your friends.

# Anonym Chat App Setup and Usage Guide / Anonim Chat Server Kurulum ve Kullanım Kılavuzu

This guide will walk u through the installation process, usage instructions, and additional details to get started with the secure and anonymous chat platform.

Hoş geldiniz! Bu kılavuz, güvenli ve anonim sohbet platformuna başlamak için kurulum sürecini, kullanım talimatlarını ve ek detayları içermektedir.

# Installation / Kurulum:

Create a new directory for the project and initialize a new Node.js project using `npm init`.

'```bash
mkdir chat-app
cd chat-app
npm init'

Clone the repository from GitHub to ur local machine:

Depoyu GitHub'dan yerel makinenize klonlayın: #

'git clone https://github.com/RoweenTheGod/Anon-Chat.git'

``
# Install Dependencies / Bağımlılıkları Yükle:

Run the following command to install the required dependencies:

"Make sure Node.js installed on ur machine."

'npm install'

``
Step 2: Install Dependencies:
$ npm install express socket.io crypto

``
Server-Side Code (app.js):

[Create a file named app.js for the server-side code.

'https://github.com/RoweenTheGod/Anon-Chat/blob/main/App.js']

[Create index.html and client.js for the client-side code.

client-Side Code (index.html, client.js):

'https://github.com/RoweenTheGod/Anon-Chat/blob/main/Client.js']

``
# Generate SSL/TLS Certificates SSL/TLS. 
• Generate self-signed SSL/TLS certificates for secure communication. • Güvenli iletişim için kendinden imzalı SSL/TLS sertifikaları oluşturun.

``
# Copy all the code and paste in terminal. / tüm kodu kopyalayıp terminale yapıştırın.

``
$ openssl req -x509 -newkey rsa:4096 -keyout server.key -out server.crt -days 365 -nodes -subj "/C=US/ST=CA/L=San Francisco/O=MyOrg/OU=MyUnit/CN=localhost"

``
# Start the Server / Sunucuyu Başlat:

To start the server, run the following command:

npm start

``
# The server will start on port 2121 by default. / Sunucu varsayılan olarak '2121' numaralı bağlantı noktasında başlayacaktır.

``
# Acess the App / Erişim:
Open a web browser and navigate to http://localhost:2121 to access the chat app. 

Bir web tarayıcısı açın ve servere erişmek için http://localhost:2121 adresine gidin

``
# App Controls / Settings/ Kontroller:

Use the chat interface to send messages, upload files, and play music.
U can send messages by typing in the input field and clicking the "Send" button.
To upload files, click the "Choose File" button, select a file from ur computer, and click the "Upload" button.
The music player allows u to play, pause, and adjust the volume of the music.

``
# Stop the Server / Sunucuyu Durdur:

To stop the server, press Ctrl + C in the terminal or command prompt where the server is running.

Sunucuyu durdurmak için, sunucunun çalıştığı terminal veya komut istemcisinde Ctrl + C tuşlarına basın.

``
# Additional Details & Tor Routing /  Ek Detaylar & Tor Yönlendirme:

All network traffic is routed through the Tor network for enhanced anonymity and privacy.
Tüm ağ trafiği, artırılmış anonimlik ve gizlilik için Tor ağı üzerinden yönlendirilir.

``
# End-to-End Encryption / Uçtan Uca Şifreleme;

Messages exchanged between clients are encrypted using AES (Advanced Encryption Standard) for message content.

İstemciler arasında alışveriş yapılan mesajlar, mesaj içeriği için AES (Advanced Encryption Standard) kullanılarak şifrelenir.

``
# RSA (Rivest-Shamir-Adleman) is used for key exchange to ensure secure communication.

Güvenli iletişimi sağlamak için anahtar değişimi için RSA (Rivest-Shamir-Adleman) kullanılır.

``
# Messages exchanged between clients are encrypted using strong cryptographic algorithms to ensure confidentiality.

İstemciler arasında alışveriş yapılan mesajlar, gizliliği sağlamak için güçlü kriptografik algoritmalar kullanılarak şifrelenir.

``
# No Logging Policy / Kayıt Tutma Politikası Yok Kral 

Aleksey'e Selamlar ;)

``
# Anonymous File Uploads / Anonim Dosya Yüklemeleri: 

Files uploaded by users are encrypted client-side before transmission to the server.

Kullanıcılar tarafından yüklenen dosyalar, sunucuya iletilmeden önce istemci tarafında şifrelenir.

``
# File Types Allowed To Send / İzin Verilen Dosya Türleri:

Users can upload any file type, including documents, images, audio files, and more. All file types are accepted.

Kullanıcılar; belgeler, resimler, ses dosyaları ve daha fazlası dahil olmak üzere her türlü dosya türünü gönderip almalarına izin verilir.

### <span style="color:#FFA500; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Meet Roween</span>

![Skull Banner](https://img.shields.io/badge/Skull-💀-000000?style=for-the-badge)

- **GitHub:** [RoweenTheGod](https://github.com/RoweenTheGod/)
- **Twitter:** [Roween's Twitter](https://x.com/RoweenTheGod?t=juGNQvoFtWgD3tds64DMng&s=09)
- **ICQ:** [Connect on ICQ](https://web.icq.com/RoweenTheGod)
- **LinkedIn:** [Roween's LinkedIn](https://it.linkedin.com/RoweenIlDio)

---

### <span style="color:#800080; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Contact Details</span>

![Contact Details Banner](https://img.shields.io/badge/Contact-Details-800080?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAMAAABEpIrGAAAAzVBMVEUAAAD///////////////////////////////////////////////////////////////////////////////////////8AYs21AAAAB3RSTlMA1KFu3PLILolj4ktzAAAAAWJLR0QAiAUdSAAAAAlwSFlzAAALEgAACxIB0t1+/AAAAd1JREFUOMutl0FPlDAQRZFYyGbZFVCzVBkYkbGKJbGz/wMzKq/6gxD4z89s12c+2bvUZ3DxeCoMs9J7EYLTM8N+ma8Mtr0ml1kBOvYbYDfAvNexIYvOQ0TwFbNb7ZzvqDXDgG3kwiN2f28Dzwdd2GSSemHpD4IZ2w4ZSbHdNgNd+DTkOzDS2K2EPdEpt0o9QoWwZpIXoiTTUI16Jk3mwx5UKk6XyCw4YjmE/jMGOCLp9kIEdS14y5PbHDN0p3QkbRG0uQ4B3lQpHp37PZVgL9HQrVLCezKEbFFUoquKlIDyWo3pdOUEqiUwG0JXt6D6iVJa4oh6tY1R7xe1cBRjkeRlEZtQKkiRRRe5iOMgApbXMQV4rNBGIcHrqgUxcSHSZF8YDoy4GFptPG0gKi9ShR2pY+JjGIGZF5FNKvL3WkJ0pt0jJPCyOsFKCZxYyaMrYwGvwnII6t6TKE8NhiYk6nSJ+8TQb7BT7/bsLfQSq3cRjCdH0U9SUS0g)
