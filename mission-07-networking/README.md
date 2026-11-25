# Mission 7 - How computers communicate

## 1. Task / objective

Explain basic network types and concepts, observe connectivity and DNS lookup information, and describe what happens when a website opens.

## 2. Work completed

I tested whether my computer can reach example.com using ping, looked up its address using nslookup, filled in a table of network concepts, and wrote a step-by-step explanation of what happens when a website opens.

## 3. Commands / tools used

- ping -c 4 example.com: sends 4 small test messages to a website and checks whether it replies.
- nslookup example.com: asks DNS for the network address that belongs to a domain name.

## 4. My understanding

### Task 7.1 - Network concepts

| Concept | In my own words | Example |
|---|---|---|
| LAN | A network in a small area where devices connect together | My home Wi-Fi |
| MAN | A network that covers a city or a large campus | A college campus network |
| WAN | A network that covers a large geographical area | The internet |
| DNS | Turns a website name into the IP address of its server | Turning example.com into a number address |
| Router | Connects networks and sends data to the right place | My Wi-Fi router |
| Protocol | A set of rules that devices follow to talk to each other | HTTP for web pages |
| Packet switching | Data is split into small packets that travel separately and are joined at the end | Sending a photo over the internet |
| Client-server | A client asks for something and a server provides it | My browser asking a website for a page |

### Task 7.2 - Observations

- **Connectivity test:** ping checks whether my computer can reach another computer and how long the reply takes. In my test, example.com replied to all 4 messages, and the replies took about WRITE-YOUR-TIME ms.
- **DNS lookup:** nslookup shows the network address (IP address) that matches a domain name, and which DNS server answered the question. I have not written the actual addresses here for privacy.
- **Role of DNS in a browser:** When I type a website name, the browser asks DNS for its address, because computers connect using addresses, not names.

### Task 7.3 - What happens when I open a website

1. I type a website name in the browser. The browser is the **client**.
2. The browser asks **DNS** to turn the name into an IP address.
3. DNS replies with the address of the website's **server**.
4. The browser sends a request using a **protocol** (HTTP or HTTPS) through my router.
5. The data travels across the network as packets, passing through other routers on the way.
6. The server receives the request, finds the page and sends back a response.
7. My browser puts the packets together and displays the web page.

## 5. Difficulties faced

No major difficulties.

## 6. How I resolved them

Not applicable.

## 7. Evidence / files

- mission-07-networking/README.md (no IP addresses or network names included)

## 8. Commit details

Commit message: "Explain networking concepts and website communication". The work was pushed to GitHub.