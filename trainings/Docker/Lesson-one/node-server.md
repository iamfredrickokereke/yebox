# Create a node server following below codes

```node

const express = require("express");

const app = express();

app.get("/", (req, res) => {
  res.send("Welcome to Yebox Devops Training Program");
});

port = process.env.PORT || 3000;

app.listen(port, () => {
  console.log(`Server is running on port ${port}`);
});


```
