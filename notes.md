


var bigX = document.querySelectorAll(".big");

var smallX = document.querySelectorAll(".small");


function countDown1 () {
        for (var i = 0; i < bigX.length; i++) {
            bigX[i].style.backgroundColor = "white";            
        }
            var time1 = setInterval (countDown1, 1000);
                countDown2 ();
    }


    function countDown2 () {
        for (var j = 0; j < bigX.length; j++) {
            bigX[j].style.backgroundColor = "black";
        }
            var time2 = setInterval (countDown2, 1000);
                countDown1 ();
    }


    function countDown3 () {
        for (var k = 0; k < smallX.length; k++) {
            smallX[k].style.backgroundColor = "black";          
        }
            var time3 = setInterval (countDown3, 1000);
                countDown4 ();
    }


    function countDown4 () {
        for (var m = 0; m < smallX.length; m++) {
            smallX[m].sytle.backgroundColor = "white";
        }
            var time4 = setInterval (countDown4, 1000);
                countDown3 ();
    }
    
    window.onload = function () {
        countDown1 ();
    };

    window.onload = function () {
        countDown2 ();
    };

=========================================================================================================================
=========================================================================================================================


 http://stackoverflow.com/questions/27494852/scaling-a-border-radius-50-class-in-chrome-doesnt-produce-a-perfect-circle

 http://stackoverflow.com/questions/2485244/window-onload-seems-to-trigger-before-the-dom-is-loaded-javascript

 http://jqueryrotate.com/

 http://stackoverflow.com/questions/11857205/how-would-i-toggle-the-state-of-a-setinterval-function-in-jquery

 http://stackoverflow.com/questions/7002039/easiest-way-to-toggle-2-classes-in-jquery




 there is no circle 54, 55, 58












