# Neumann-Fornax-Assignment

<div class='holder'>
  <div class="square">
    <div class='content'>

    </div>
  </div>
</div>


.holder {
  width: 40px;//or a percentage it will still be a square
 }

.square {
  position: relative;
  width: 100%;
  border-top: 3px solid black;
  border-bottom: 3px solid black;
  border-right: 3px solid black;
  border-left: 3px solid black;
}

.square:after {
  content: "";
  display: block;
  padding-bottom: 100%;
}

.content {
  position: absolute;
  width: 100%;
  height: 100%;
}
