<style>
.outer {
  display: inline-block;
  padding: 10px 20px;
  background-color: #f44336;
  color: white;
  border-radius: 8px;
  cursor: pointer;
  position: relative;
}

.middle {
  display: inline-block;
  padding: 10px 20px;
  background-color: #f44336;
  color: white;
  border-radius: 6px;
  cursor: pointer;
  position: relative;
}

.inner {
  display: inline-block;
  padding: 10px 20px;
  background-color: #f44336;
  color: white;
  border-radius: 4px;
  cursor: pointer;
}
</style>

<body>
  <div id="header" aling="center">
   <h1></h1>
  </div>
  <div class="outer" onclick="alert('Outer clicked!')">
    Don't push this button
    <div class="middle" onclick="event.stopPropagation(); alert('Middle clicked!')">
      I see. Don't push!
      <div class="inner" onclick="event.stopPropagation(); window.location.href='https://www.youtube.com/watch?v=dQw4w9WgXcQ';">
        OK.
      </div>
    </div>
  </div>
</body>
