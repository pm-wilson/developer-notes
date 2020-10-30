## Node Notes

- Disable Cors from Server:

Install:
npm install --save cors

Add to App.js:
const cors = require('cors');

app.use(cors({
  origin: true,
  credentials: true
}));


- 
