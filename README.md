Demo Link [Demo](https://sandip-fullstack.github.io/Speech-Based-E-commerce/)

This is a very basic E-commerce site with some dummy items. The interesting part of this project is that the site can be controlled using your own voice command. You can Sort items based on price, date. You can search your favourites items also.
You can buy items(offcourse not in real).
UI framework: React JS,
Backend: Node JS, Express JS,
Voice Processing: Annyang, Speechkiit

Below are some voice commands to try.
1. 'Filter by *price' -- Filter by low to high, Filter by High to low, Filter by date
2. 'show me *item' -- show me mobile
3. 'search'
4. 'clear search'
5. 'play *song song' -- play cheap thrills song
6. 'check out number *number' -- checkout number 2
7. 'cancel check out'
8. 'continue to pay'
9. 'Bank name *bank' -- Bank name ICICI
10. 'card number *card' -- card number 12345678
11. 'pin number *pin' -- pin number 1234
12. 'pay now'
13. 'Search *term in google' -- search camera in google

Steps to run project:
1. Clone the repo
2. npm install
3. run ./ngork http 80 (where you have downloaded ngork)
4. npm start
5. Take the url from ngork

If you don't want the project to run in HTTPS, ignore step 3 and 5. You can directly run localhost:8080

P.s: Voice recognition will be efficient if HTTPS is used.
