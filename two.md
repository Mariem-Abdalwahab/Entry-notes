# Basic Network Concepts

# **The Internet and the Web**

- • 📹 [How does the INTERNET work?](https://youtu.be/x3c1ih2NJEg)
    
    Data center stored video inside it…how it reach me here is the use of **satellites**
    
    It is stored in a **Solid-State Device** in the data center **SSD**
    
    ## First method (not a good method)
    
    - from data center to the satellite to my phone via an antenna
    - It take along time until it reach it’s destination
    - it cause an delay with the signal
    
    ## Second method (good method)
    
    - it does with the help of complicated network of **optical fiber cables**
    - connect between Data Center and your device
    - your phone can be connected via **Cellular** or Wi-Fi
    - **SSD** acts as the internal memory of a server
    - **server is a powerful computer whose job is to provide you the video or any content or data you request**
    
    ## How data transfer from data center to you specifically?
    
    1. server of the data center has an IP address
    2. server store the website… just know the IP of the server
    3. DNS turn the domain name to IP address it is simplify the process
    4. the data transferred  in a digital format via fiber cables (light pulses)
    5. light pulses go to the router and it convert it to a electrical signals
    6. if you use computer the signal will transfer through the cable
    7. if you use Cellular the signal will send to cell tower then will reach your phone in the form of electromagnetic wave

# **The Client Server Architecture**

- • 📹 [The Client Server Architecture from The TechCave](https://www.youtube.com/watch?v=L5BlpPU_muY)
    
    ## What is the client ?
    
    Client can be ⇒ machine or program (phone or computer) or(web browser that make a request  )
    
    ## What is a server ?
    
    - Server is a computer program not a device
    - Server it is a High-performance computer (cause it run server program)
    - server provide functionality and serve other program called client
    - one server can serve multiple clients
    - can run multiple server on one machine called virtual servers
    - it can contain web resource, host web application, stores user and data
    
    ## How does the client-server model works ?
    
    - Client-server → Centralized structure
    - Centralized structure X  decentralized structure
    - decentralized structure it is a Peer-To-Peer model
    
    ### Peer-To-Peer model
    
    - no client no server
    - both can do request and response
    - BitTorrent and Videochat protocols are example of it
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/60aea896-f6e4-454a-834d-7cebd90bbb19/Untitled.png)
    

# **HTTP Protocol**

- Hypertext Transfer Protocol
- It help web-based application to communicate and exchange data
- It is the messenger of the web
- it is a TCP/IP passed protocol
- it used to deliver data
- HTTP is connectionless: when request send the wed disconnect with the server and when the response is steady the connection comeback
- HTTP is stateless: when the connection completely closed the client and server doesn’t know each other

### Why HTTP?

It is created first to fetch HTML documents

 

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/0a237a2f-f25e-47d7-9082-5a4aaf9d0bbe/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/94404c8d-4b51-4331-bb6d-92e8abbf1528/Untitled.png)

### Request HTTP message

1. Method : is a command to tell the server what to do
2. URl: is a readable content to locate the resource
3. Header: type of the file, the language and where to but this information

### Response HTTP message

1. status code: if the request succeeded or not
2. file we want