# Soho Nails: Scheduling and Calendar Management System

My family owns a nail spa in Maracaibo, Venezuela. They used to make all appointments by hand, when I started learning how to program at FIU, an idea popped into my head. "There must be a better way of doing this"


## Tech Stack 1.0

**Client:** Java

**Server:** PHP, MySQL
## Screenshots

![App Screenshot](https://i.imgur.com/QNF3AHI.jpeg)

## Lessons

- Timed refresh is not a good idea (AWS got really expensive)
- Using a web portal to let customers confirm their own appointments by SMS proved to work very well
- Had to find a way to make the dashboard only update when needed

## Tech Stack Version 2.0

**Admin Dashboard:** Flutter

**Client Web App:** Flutter

**Server:** PHP, MySQL, WebSockets


## Screenshots

![App Screenshot](https://i.imgur.com/toDLsyX.jpeg)

![Web Portal](https://i.imgur.com/HFidBqQ.png)

## Lessons

- Using WebSockets to ping all clients to update brought down AWS cost from +$100 to around $30 - $40
- A web app only for clients to create their own appointments improved our total appointments per day.
