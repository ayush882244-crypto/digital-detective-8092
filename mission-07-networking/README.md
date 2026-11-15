# mission 7 - how computers communicate

## 1 task / objective
explain network types and concepts observe connectivity and dns lookup and describe steps when opening a website

## 2 work completed
completed network concepts table with simple examples
ran connectivity ping test and dns lookup for example.com
wrote step by step explanation of website loading process

## 3 commands / tools used
- ping -c 2 example.com: check network connectivity and packet loss
- dig +short example.com: perform dns lookup to find ip address of domain

## 4 my understanding

### task 7.1 - network concepts table
| concept | explain it in your own words | example |
| --- | --- | --- |
| lan | local area network covering a small area | home wifi network connecting laptop and phone |
| man | network covering a city or university campus | college campus network linking all departments |
| wan | network spanning large geographical areas or worldwide | the global internet |
| dns | translates human readable website name into numerical ip address | translates example.com to 172.66.147.243 |
| router | device that routes data packets between different networks | home wifi router forwarding traffic to isp |
| protocol | standard set of rules for devices to communicate | http and https protocols |
| packet switching | dividing data into small chunks that travel independently over network | downloading a webpage file |
| client-server | architecture where client requests resources and server delivers them | web browser requesting page from remote web server |

### task 7.2 - network observations
- what a connectivity test helps you check:
  ping checks if a remote server can be reached and measures response latency and packet loss
- what information a dns lookup displays:
  it displays the public ip addresses mapped to a domain name
- role of dns when entering a website name:
  browsers cannot route using domain names directly so dns resolves the domain to an ip address so packets reach correct server
- observation:
  ping to example.com had 0.0% packet loss and dig returned ip 172.66.147.243

### task 7.3 - what happens when you open a website
1. user types url into client web browser
2. browser asks dns server to find ip address for domain name
3. dns server returns ip address of web server to client
4. client computer sends connection request packets routed through local router and internet
5. client browser and web server establish connection using https protocol
6. web server processes request and sends back website data packets
7. client browser renders html css and javascript to display webpage to user

## 5 difficulties faced
understanding why computers use ip addresses instead of domain names

## 6 how i resolved them
learned that routers route packets efficiently using numerical ip addresses and dns translates names for humans

## 7 evidence / files
- ping and dig command outputs recorded in this readme

## 8 commit details
commit message: explain networking concepts and website communication
