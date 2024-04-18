# What Happens When I Type "https://www.google.com" in My Browser?
====================

Have you ever wondered what goes on behind the scenes when you hit that enter key after typing a web address into your browser? Well, I have always wondered. It takes a lot of processes before webpages get loaded on our browsers. This involves various layers of technology working seamlessly to deliver the content. In this post, I’ll try to unravel the mystery step by step, from the moment I initiate the request to the moment I see the webpage rendered on my screen.
1. DNS Request:
My browser resolves the domain name “www.google.com" to an IP address, by sending a Domain Name System (DNS) request to a DNS server. This maps the domain names to an IP address (in my case “www.google.com" resolves to “8.8.8.8”). Once the IP address is obtained, my browser can communicate with the server hosting the website.
2. TCP/IP:
With the IP address in hand, my browser establishes a Transmission Control Protocol (TCP) connection to the server. TCP ensures reliable and ordered delivery of data packets over the internet. It sets up a connection with the server using a handshake mechanism before data exchange begins.
3. Firewall:
Before my request reaches the server, it may encounter a firewall. Firewalls are network security devices that monitor and control incoming and outgoing traffic based on predetermined security rules. If my request passes through the firewall successfully, it proceeds to the next step.
4. HTTPS/SSL:
The communication between my browser and the server is encrypted using HTTPS (Hypertext Transfer Protocol Secure) and SSL (Secure Sockets Layer) or its successor TLS (Transport Layer Security). This ensures that sensitive information, such as login credentials or personal data, remains private and secure during transmission. 
5. Load-Balancer:
Load balancers try to distribute incoming traffic across multiple servers. Load balancers enhance reliability, scalability, and performance by efficiently managing the workload and preventing any single server from being overwhelmed. Large companies like Google have load balancers and it means that when I send a request via a browser, my request gets assigned to an available server.
6. Web Server:
Once my request reaches the appropriate server, a web server software, such as Apache or Nginx, processes it. The web server retrieves the requested web page or resource from storage and prepares it for delivery back to my browser.
7. Application Server:
In some cases, especially for dynamic web applications, the web server may communicate with an application server. The application server executes the necessary logic, such as retrieving data from a database or processing user inputs, before generating the final content to be sent back to my browser.
8. Database:
If the requested web page relies on data stored in a database, the application server queries the database to retrieve the relevant information. This data is then integrated into the web page before it is sent back to my browser for rendering.
Now you see! It takes a lot of processes before my requested webpage gets loaded on my browser. Next time you type a web address and press enter, remember the complex orchestration that happens behind the scenes to bring you the information you seek. Understanding this process gives us a deeper appreciation for the wonders of the internet.

.. _`Creative Commons Zero`: https://creativecommons.org/publicdomain/zero/1.0/
.. _`"CSS lexical and syntax grammar"`: http://www.w3.org/TR/CSS2/grammar.html
.. _`Punycode`: https://en.wikipedia.org/wiki/Punycode
.. _`Ethernet`: http://en.wikipedia.org/wiki/IEEE_802.3
.. _`WiFi`: https://en.wikipedia.org/wiki/IEEE_802.11
.. _`Cellular data network`: https://en.wikipedia.org/wiki/Cellular_data_communication_protocol
.. _`analog-to-digital converter`: https://en.wikipedia.org/wiki/Analog-to-digital_converter
.. _`network node`: https://en.wikipedia.org/wiki/Computer_network#Network_nodes
.. _`TCP congestion control`: https://en.wikipedia.org/wiki/TCP_congestion_control
.. _`cubic`: https://en.wikipedia.org/wiki/CUBIC_TCP
.. _`New Reno`: https://en.wikipedia.org/wiki/TCP_congestion_control#TCP_New_Reno
.. _`congestion window`: https://en.wikipedia.org/wiki/TCP_congestion_control#Congestion_window
.. _`maximum segment size`: https://en.wikipedia.org/wiki/Maximum_segment_size
.. _`varies by OS` : https://en.wikipedia.org/wiki/Hosts_%28file%29#Location_in_the_file_system
.. _`简体中文`: https://github.com/skyline75489/what-happens-when-zh_CN
.. _`한국어`: https://github.com/SantonyChoi/what-happens-when-KR
.. _`日本語`: https://github.com/tettttsuo/what-happens-when-JA
.. _`downgrade attack`: http://en.wikipedia.org/wiki/SSL_stripping
.. _`OSI Model`: https://en.wikipedia.org/wiki/OSI_model
.. _`Spanish`: https://github.com/gonzaleztroyano/what-happens-when-ES
