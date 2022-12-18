# How do these concepts relate to websites and applications users access over the Internet?

Consider this article. In order for you to see it, it was sent over the Internet piece by piece in the form of several thousand data packets. These packets traveled over cables and radio waves and through routers and switches from our web server to your computer or device. Your computer or smartphone received those packets and passed them to your device's browser, and your browser interpreted the data within the packets in order to display the text you are reading now.The specific steps involved in this process are:

1. DNS query: When your browser started to load this webpage, it likely first made a DNS query to find out the Cloudflare website's IP address.
2. TCP handshake: Your browser opened a connection with that IP address.
3. TLS handshake: Your browser also set up encryption between a Cloudflare web server and your device so that attackers cannot read the data packets that travel between those two endpoints.
4. HTTP request: Your browser requested the content that appears on this webpage.
5. HTTP response: Cloudflare's server transmitted the content in the form of HTML, CSS, and JavaScript code, broken up into a series of data packets. Once your device received the packets and verified it had received all of them, your browser interpreted the HTML, CSS, and JavaScript code contained in the packets to render this article about how the Internet works. The whole process took only a second or two.
