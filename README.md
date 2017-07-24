# Kitty-Fisher
<!DOCTYPE html>
<html>
;(function () {
  function main( tFrame ) {
    MyGame.stopMain = window.requestAnimationFrame( main );    
    update( tFrame ); 
    render();
  }  
  main(); // Start the cycle
})();
window.cancelAnimationFrame( MyGame.stopMain );
var tNow = window.performance.now();
</html>
