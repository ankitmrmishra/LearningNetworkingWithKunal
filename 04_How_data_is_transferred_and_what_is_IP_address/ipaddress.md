## Data Sharing over Networks

Nowadays we open an app and send the data within seconds(thanks to the internet connection speed) and receive it from the other end and we often perform this process on daily basis, ***in fact, according to*** [***TechJury***](https://techjury.net/blog/how-much-data-is-created-every-day/#:~:text=Given%20how%20much%20data%20is,1.145%20trillion%20MB%20per%20day.) ***In 2021, people created 2.5 quintillion bytes of data every day*** and this is a very large amount of data and this amount of data creation and sharing is done Binary Digits i.e. ***0's and 1's***

But sharing a large file of say 1GB in binary form(because that's what a computer generates and shares) is very problematic when we are sending all the data at once. Instead, data over networks is shared in patches/chunks known as ***Packets.***

> `According To definition I found on the internet "packets are the small units of a large Data which is used to share the information over a network"`
> 
> Let's understand how data is transferred over a network using Packets
> 
> Suppose Anmol has to send an assignment of an Engineering Drawing sheet which is of A0 size to Shobhit but Shobhit's MailBox can maximum take a size of A4.
> 
> So instead of sending the Data of the A0 paper, Anmol divides the information of the EGD assignment and Writes it into an A4 sheet which shobhit will receive and will rearrange according to the set of rules.
> 
> In the same way, Packets work as A4 sheets and transfer data over the network
> 
> `(A complete detailed blog about how data is transferred over networks will be published Later)`

## **Now coming to the most important part of the blog i.e.** ***IP address***



### What is IP Address?

When I was in Primary School I used to play Cricket in the playground day and night and my mom used to send someone passing by my house with a message "Please tell ANKIT to go home and eat food and other stuff". 20-25 children were playing there But How did that person send me only the message of my mother? That is very clear Because he knows my name and remembers it.

In the same way, every computer connected to the network has a particular name by which it is identified over a Network.

The IP address is of the form `X.X.X.X` . Each X can have a value from \[0-255\].

### So how do we get an IP address and How it works?

The answer is an Internet Service provider(ISP) gives us an IP address for example in India there Are few ISPs like JIO, AIRTEL, VI, etc., so these ISPs provide Us a modem/Router which has a ***Global IP Address,*** all the devices connected through this modem/router will have same IP Address*.* The Modem will also provide ***Local IP Addresses*** to the devices connected through the Modem/Router and is done by *Dynamic Host Configuration Protocol (****DHCP****)*

Now let's say from a router/modem many devices are connected and one of the device tries to access some information from internet, so how does internet will send the information to that particular device only? When the request for accessing the information is sent to the internet, internet will send it to the modem/router and router/modem will now decide which device to send and it does it by *Network Access Translator(****NAT****),* and now the application which did the Request , the data is sent to it by ***ports****.*

`Learn more about it from the best Computer Networking course from @[Kunal Kushwaha](@kunalk)'s Youtube Channel`

[WAtch Video Here](https://youtu.be/IPvYjXCsTg8)

More Blogs will be coming in future related to computer networking.

## Connect with ME!!

1.  [Connect on Twitter](https://twitter.com/AnkitMishraexe)
    
2.  [Connect on GITHUB](https://github.com/ankitmrmishra)
    
3.  [Connect on Linkedin](https://linkedin.com/in/ankitmishra1106)
