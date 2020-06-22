function downloadImage(data, filename = 'untitled') {
    var a = document.createElement('a');
    a.href = data;
    a.download = filename;
    document.body.appendChild(a);
    a.click();
}

$(document.getElementById('canvas')).ready(function() {
    localStorage.gallery_1 = "zLlUYw{c";
    localStorage.gallery_2 = "WFzjS4JL";
    localStorage.gallery_3 = "*}MyM#{Q";
    localStorage.gallery_4 = "n*a$G]!}";
    localStorage.gallery_5 = "K!!FAF{E";
    localStorage.gallery_6 = "44BU(%!J";
    localStorage.gallery_7 = "byPj@}{&";
    localStorage.gallery_8 = "MMwNDUJx";
    localStorage.gallery_9 = "6GJc]c{2";
    localStorage.gallery_10 = "dAXr%kJl";
    localStorage.gallery_11 = "A(768W{q";
    localStorage.gallery_12 = "u@{{2eJv";
    localStorage.gallery_13 = "R5MNwm{e";
    localStorage.gallery_14 = "@zwyquJj";
    localStorage.gallery_15 = "iX!$k2{S";
    localStorage.gallery_16 = "%xEqJb!u";
    localStorage.gallery_17 = "lrSEDj{d";
    localStorage.gallery_18 = "Il2T]r!i";
    localStorage.gallery_19 = "2f*iNz{R";
    localStorage.gallery_20 = "ZZdxH7!W";
    localStorage.gallery_21 = "[Tr#B&{b";
    localStorage.gallery_22 = "q%5E)1!K";
    localStorage.gallery_23 = "N8ST#9{P";
    localStorage.gallery_24 = "{sz]5H!]";
    localStorage.gallery_25 = "sm$MzP{3";
    localStorage.gallery_26 = "PgabtX!8";
    localStorage.gallery_27 = "9EoqnJ{$";
    localStorage.gallery_28 = "g{25hR!w";
    localStorage.gallery_29 = "D&P]bZ{1";
    localStorage.gallery_30 = "x9dMVh!k";
    localStorage.gallery_31 = "U3$bPp{p";
    localStorage.gallery_32 = "hynlyNJ}";
    localStorage.mob_1 = "qlCHeI9z";
    localStorage.mob_2 = "[rp&kA]u";
    localStorage.mob_3 = "Z[beqO9@";
    localStorage.mob_4 = "vHpHAa]g";
    localStorage.mob_5 = "BNF&GS9b";
    localStorage.mob_6 = "eT%0Mg]s";
    localStorage.mob_7 = "7Z0lSY9n";
    localStorage.mob_8 = "G6sO{k]I";
    localStorage.mob_9 = "j#e}Ey9Z";
    localStorage.mob_10 = "#)Ql@q]U";
    localStorage.mob_11 = "SB3W(i9P";
    localStorage.mob_12 = "oM(}x*yG";
    localStorage.mob_13 = "(S37389B";
    localStorage.mob_14 = "XYTs90][";
    localStorage.mob_15 = "00Fd&s9N";
    localStorage.mob_17 = "4b}XzV9c";
    localStorage.mob_18 = "4b}XzV9c";
    localStorage.mob_19 = "nnu*@b9o";
    localStorage.mob_20 = "9ymXVn]J";
    localStorage.mob_21 = "P4YIbf9a";
    localStorage.mob_22 = "s!K*ht]V";
    window.onmousemove = function() { if ( document.getElementById("canvas").style.cursor == "default") { document.getElementById("canvas").style.cursor = "crosshair"; } };
    document.getElementById("canvas").style.cursor = "crosshair";
    var Playing = false;
    var overlay = document.createElement("div");
    overlay.style = "pointer-events: none; position: fixed; top:20px; left:10px; font-family: 'Comic Sans MS', cursive, sans-serif; color: rgba(255,255,255,0.5); font-style: normal; font-variant: normal;-webkit-touch-callout: none;-webkit-user-select: none;-khtml-user-select: none;-moz-user-select: none;-ms-user-select: none;user-select: none;outline: 0;";
    document.body.appendChild(overlay);
    devicePixelRatio = Number(localStorage.devicePixelRatio) || 2;
    overlay.innerHTML = `<p>•O- or P+ for pixel ratio [${Math.round(Number(devicePixelRatio)*100)/100}] (lower = better fps)</p>`
    overlay.className = "menu";
    var overlay1 = document.createElement("div");
    overlay1.style = "pointer-events: none; position: fixed; top:40px; left:10px; font-family: 'Comic Sans MS', cursive, sans-serif; color: rgba(255,255,255,0.5); font-style: normal; font-variant: normal;-webkit-touch-callout: none;-webkit-user-select: none;-khtml-user-select: none;-moz-user-select: none;-ms-user-select: none;user-select: none;outline: 0;";
    overlay1.className = "menu";
    document.body.appendChild(overlay1);
    var stepTime = localStorage.stepTime || 45;
    overlay1.innerHTML = `<p>•L- or M+ for switch speed change [${stepTime}ms]</p>`
    var overlay2 = document.createElement("div");
    overlay2.style = "pointer-events: none; position: fixed; top:60px; left:10px; font-family: 'Comic Sans MS', cursive, sans-serif; color: rgba(255,255,255,0.5); font-style: normal; font-variant: normal;-webkit-touch-callout: none;-webkit-user-select: none;-khtml-user-select: none;-moz-user-select: none;-ms-user-select: none;user-select: none;outline: 0;";
    overlay2.className = "menu";
    document.body.appendChild(overlay2);
    var fLocked = false;
    overlay2.innerHTML = `<p>•Use F to delete the last petal from your stored slots and CTRL+F to lock ${fLocked? '<a style="color:red">[' : '<a style="color:green">[NOT '}LOCKED]</a></p>`
    var overlay3 = document.createElement("div");
    overlay3.style = "pointer-events: none; position: fixed; top:80px; left:10px; font-family: 'Comic Sans MS', cursive, sans-serif; color: rgba(255,255,255,0.5); font-style: normal; font-variant: normal;-webkit-touch-callout: none;-webkit-user-select: none;-khtml-user-select: none;-moz-user-select: none;-ms-user-select: none;user-select: none;outline: 0;";
    overlay3.className = "menu";
    document.body.appendChild(overlay3);
    overlay3.innerHTML = `<p>•Use from W up to ; key toggle from the 1st up to 8th petal</p>`
    var overlay7 = document.createElement("div");
    overlay7.style = "pointer-events: none; position: fixed; top:100px; left:10px; font-family: 'Comic Sans MS', cursive, sans-serif; color: rgba(255,255,255,0.5); font-style: normal; font-variant: normal;-webkit-touch-callout: none;-webkit-user-select: none;-khtml-user-select: none;-moz-user-select: none;-ms-user-select: none;user-select: none;outline: 0;";
    overlay7.className = "menu";
    document.body.appendChild(overlay7);
    overlay7.innerHTML = `<p>between stored and active slots</p>`
    var overlay6 = document.createElement("div");
    overlay6.style = "pointer-events: none; position: fixed; top:120px; left:10px; font-family: 'Comic Sans MS', cursive, sans-serif; color: rgba(255,255,255,0.5); font-style: normal; font-variant: normal;-webkit-touch-callout: none;-webkit-user-select: none;-khtml-user-select: none;-moz-user-select: none;-ms-user-select: none;user-select: none;outline: 0;";
    overlay6.className = "menu";
    document.body.appendChild(overlay6);
    var wavy = localStorage.wavy || "false";
    var wavySpeed = localStorage.wavySpeed || 420;
    overlay6.innerHTML = `<p>•Use R to toggle wavy mode [${wavy==1? "ATK+DEF" :wavy==2? "ATK" :wavy==3? "DEF" : "OFF"}] of interval ${wavySpeed}ms (U- I+)</p>`
    var overlay8 = document.createElement("div");
    overlay8.style = "pointer-events: none; position: fixed; top:140px; left:10px; font-family: 'Comic Sans MS', cursive, sans-serif; color: rgba(255,255,255,0.5); font-style: normal; font-variant: normal;-webkit-touch-callout: none;-webkit-user-select: none;-khtml-user-select: none;-moz-user-select: none;-ms-user-select: none;user-select: none;outline: 0;";
    overlay8.className = "menu";
    document.body.appendChild(overlay8);
    var widest = localStorage.widest || "true"
    overlay8.innerHTML = `<p>•Use K to toggle between original and widest area view [${widest=="true"?"ON":"OFF"}]</p>`
    var overlay5 = document.createElement("div");
    overlay5.style = "pointer-events: none; position: fixed; top:190px; left:10px; font-family: 'Comic Sans MS', cursive, sans-serif; color: rgba(255,0,0,0.5); font-style: normal; font-variant: normal;-webkit-touch-callout: none;-webkit-user-select: none;-khtml-user-select: none;-moz-user-select: none;-ms-user-select: none;user-select: none;outline: 0;";
    document.body.appendChild(overlay5);
    overlay5.innerHTML = `<p>[PRESS ENTER FIRST]</p>`
    var overlay4 = document.createElement("div");
    overlay4.style = "pointer-events: none; position: fixed; top:160px; left:10px; font-family: 'Comic Sans MS', cursive, sans-serif; color: rgba(255,255,255,0.5); font-style: normal; font-variant: normal;-webkit-touch-callout: none;-webkit-user-select: none;-khtml-user-select: none;-moz-user-select: none;-ms-user-select: none;user-select: none;outline: 0;";
    overlay4.className = "menu";
    document.body.appendChild(overlay4);
    overlay4.innerHTML = `<p>•Use Z to toggle menu display</p>`
    var eventObj;
    var eventObj1;
    var eventObj2;
    var oktoggle = true;
    var okbin = true;
    function lockbin() {
        if (fLocked) {
            eventObj = document.createEvent("Events"); eventObj.initEvent('keydown', true, true); eventObj.keyCode = 27; window.dispatchEvent(eventObj);
            eventObj = document.createEvent("Events"); eventObj.initEvent('keyup', true, true); eventObj.keyCode = 27; window.dispatchEvent(eventObj);
        }
        setTimeout(function(){
            if (fLocked) {
                eventObj = document.createEvent("Events"); eventObj.initEvent('keydown', true, true); eventObj.keyCode = 81; window.dispatchEvent(eventObj);
                eventObj = document.createEvent("Events"); eventObj.initEvent('keyup', true, true); eventObj.keyCode = 81; window.dispatchEvent(eventObj);
            }
            setTimeout(function(){
                if (fLocked) {
                    eventObj = document.createEvent("Events"); eventObj.initEvent('keydown', true, true); eventObj.keyCode = 84; window.dispatchEvent(eventObj);
                    eventObj = document.createEvent("Events"); eventObj.initEvent('keyup', true, true); eventObj.keyCode = 84; window.dispatchEvent(eventObj);
                }
                setTimeout(function(){
                    if (fLocked) {
                        eventObj = document.createEvent("Events"); eventObj.initEvent('keydown', true, true); eventObj.keyCode = 27; window.dispatchEvent(eventObj);
                        eventObj = document.createEvent("Events"); eventObj.initEvent('keyup', true, true); eventObj.keyCode = 27; window.dispatchEvent(eventObj);
                    }
                    setTimeout(function(){
                        lockbin()
                    },stepTime)
                },stepTime)
            },stepTime)
        },stepTime)
    }
    lockbin();
    var keyss = {8: false, 9: false, 13: false, 16: false, 17: false, 18: false, 20: false, 27: false, 32: false, 35: false, 36: false, 37: false, 48: false, 49: false, 50: false, 51: false, 52: false, 53: false, 54: false, 55: false, 56: false, 57: false, 65: false, 66: false, 67: false, 68: false, 69: false, 70: false, 71: false, 72: false, 73: false, 74: false, 75: false, 76: false, 77: false, 78: false, 79: false, 80: false, 81: false, 82: false, 83: false, 84: false, 85: false, 86: false, 87: false, 88: false, 89: false, 90: false, 91: false, 93: false, 186: false, 187: false, 188: false, 189: false, 190: false, 191: false, 192: false, 219: false, 220: false, 221: false, 222: false, 229: false};
    onkeydown = onkeyup = function(e){
        e = e || event; // to deal with IE
        keyss[e.keyCode] = e.type == 'keydown';
        if (e.keyCode == 70 && keyss[e.keyCode] && okbin) {
            if (!e.ctrlKey) {
                okbin = false;
                eventObj = document.createEvent("Events"); eventObj.initEvent('keydown', true, true); eventObj.keyCode = 27; window.dispatchEvent(eventObj);
                eventObj = document.createEvent("Events"); eventObj.initEvent('keyup', true, true); eventObj.keyCode = 27; window.dispatchEvent(eventObj);
                setTimeout(function(){
                    eventObj = document.createEvent("Events"); eventObj.initEvent('keydown', true, true); eventObj.keyCode = 81; window.dispatchEvent(eventObj);
                    eventObj = document.createEvent("Events"); eventObj.initEvent('keyup', true, true); eventObj.keyCode = 81; window.dispatchEvent(eventObj);
                    setTimeout(function(){
                        eventObj = document.createEvent("Events"); eventObj.initEvent('keydown', true, true); eventObj.keyCode = 81; window.dispatchEvent(eventObj);
                        eventObj = document.createEvent("Events"); eventObj.initEvent('keyup', true, true); eventObj.keyCode = 81; window.dispatchEvent(eventObj);
                        setTimeout(function(){
                            eventObj = document.createEvent("Events"); eventObj.initEvent('keydown', true, true); eventObj.keyCode = 84; window.dispatchEvent(eventObj);
                            eventObj = document.createEvent("Events"); eventObj.initEvent('keyup', true, true); eventObj.keyCode = 84; window.dispatchEvent(eventObj);
                            setTimeout(function(){
                                eventObj = document.createEvent("Events"); eventObj.initEvent('keydown', true, true); eventObj.keyCode = 27; window.dispatchEvent(eventObj);
                                eventObj = document.createEvent("Events"); eventObj.initEvent('keyup', true, true); eventObj.keyCode = 27; window.dispatchEvent(eventObj);
                                okbin = true;
                            },stepTime)
                        },stepTime)
                    },stepTime*1.5)
                },stepTime)
            } else {
                fLocked = !fLocked
                overlay2.innerHTML = `<p>•Use F to delete the last petal from your stored slots and CTRL+F to lock ${fLocked? '<a style="color:red">[' : '<a style="color:green">[NOT '}LOCKED]</a></p>`
            }
        }
        if ((keyss[87]||keyss[88]||keyss[67]||keyss[86]||keyss[66]||keyss[78]||keyss[188]||keyss[186]) && oktoggle && e.key != "<") {
            oktoggle = false;
            toggleSA(keyss[87]?49:keyss[88]?50:keyss[67]?51:keyss[86]?52:keyss[66]?53:keyss[78]?54:keyss[188]?55:56)
        }
        if (e.keyCode == 13 && keyss[13] && !Playing) {
            Playing = true;
            overlay5.style.display = "none"
        }
        if (Playing) {
            if (e.keyCode == 79 && keyss[79]) {
                if (Math.round(Number(devicePixelRatio)*100)/100-0.1 > 0) {
                    devicePixelRatio = Math.max(0.1,Number(devicePixelRatio)-0.1)
                    localStorage.devicePixelRatio = Number(devicePixelRatio);
                    overlay.innerHTML = `<p>•O- or P+ for pixel ratio [${Math.round(Number(devicePixelRatio)*100)/100}] (lower = better fps)</p>`
                    window.innerWidth -= 1
                }
            } else if (e.keyCode == 80 && keyss[80]) {
                devicePixelRatio  = Number(devicePixelRatio)+0.1
                localStorage.devicePixelRatio = Number(devicePixelRatio);
                overlay.innerHTML = `<p>•O- or P+ for pixel ratio [${Math.round(Number(devicePixelRatio)*100)/100}] (lower = better fps)</p>`
                window.innerWidth += 1
            }
            if (e.keyCode == 76 && keyss[76]) {
                stepTime = Math.max(0,stepTime-1)
                localStorage.stepTime = stepTime;
                overlay1.innerHTML = `<p>•L- or M+ for switch speed change [${stepTime}ms]</p>`
            } else if (e.keyCode == 77 && keyss[77]) {
                stepTime++
                localStorage.stepTime = stepTime;
                overlay1.innerHTML = `<p>•L- or M+ for switch speed change [${stepTime}ms]</p>`
            }
            if (e.keyCode == 90 && !keyss[90]) {
                for (var i = 0; i < document.getElementsByClassName("menu").length; i++) {
                    document.getElementsByClassName("menu")[i].style.display = document.getElementsByClassName("menu")[i].style.display != "none"? "none" : "block";
                }
            }
            if (e.keyCode == 82 && keyss[82]) {
                wavy = wavy=="false"? 1 : wavy==1? 2 : wavy==2? 3 : "false";
                localStorage.wavy = wavy;
                overlay6.innerHTML = `<p>•Use R to toggle wavy mode [${wavy==1? "ATK+DEF" :wavy==2? "ATK" :wavy==3? "DEF" : "OFF"}] of interval ${wavySpeed}ms (U- I+)</p>`
                if (wavy == "false") {
                    eventObj2 = document.createEvent("Events"); eventObj2.initEvent('keyup', true, true); eventObj2.keyCode = 16; window.dispatchEvent(eventObj2);
                    eventObj2 = document.createEvent("Events"); eventObj2.initEvent('keyup', true, true); eventObj2.keyCode = 32; window.dispatchEvent(eventObj2);
                } else if (wavy == 2) {
                    eventObj2 = document.createEvent("Events"); eventObj2.initEvent('keyup', true, true); eventObj2.keyCode = 16; window.dispatchEvent(eventObj2);
                } else if (wavy == 3) {
                    eventObj2 = document.createEvent("Events"); eventObj2.initEvent('keyup', true, true); eventObj2.keyCode = 32; window.dispatchEvent(eventObj2);
                }
            }
            if (e.keyCode == 73 && keyss[e.keyCode]) {
                var dataURL = document.getElementById('canvas').toDataURL("image/png", 1.0);
                downloadImage(dataURL, localStorage.florrio_nickname+' - florr.io.png');
            }
            if (e.keyCode == 85 && keyss[85]) {
                wavySpeed = Math.max(wavySpeed-1,1)
                localStorage.wavySpeed = wavySpeed;
                overlay6.innerHTML = `<p>•Use R to toggle wavy mode [${wavy==1? "ATK+DEF" :wavy==2? "ATK" : "OFF"}] of interval ${wavySpeed}ms (U- I+)</p>`
            } else if (e.keyCode == 73 && keyss[73]) {
                wavySpeed++
                localStorage.wavySpeed = wavySpeed;
                overlay6.innerHTML = `<p>•Use R to toggle wavy mode [${wavy==1? "ATK+DEF" :wavy==2? "ATK" : "OFF"}] of interval ${wavySpeed}ms (U- I+)</p>`
            }
            if (e.keyCode == 75 && keyss[75]) {
                widest = widest=="true"?"false":"true";
                localStorage.widest = widest;
                overlay8.innerHTML = `<p>•Use K to toggle between original and widest area view [${widest=="true"?"ON":"OFF"}]</p>`
                if (widest=="true") {
                    window.innerWidth -= 1
                } else {
                    document.getElementById("canvas").width = devicePixelRatio*innerWidth
                    document.getElementById("canvas").height = devicePixelRatio*innerHeight
                    window.innerWidth += 1
                }
            }
        }
    }
    function wavyInt() {
        setTimeout(function(){
            if (wavy != "false") {
                setTimeout(function(){
                    if (wavy != "false") {
                        if (wavy != 3) {
                            eventObj2 = document.createEvent("Events"); eventObj2.initEvent('keydown', true, true); eventObj2.keyCode = 32; window.dispatchEvent(eventObj2);
                        } else {
                            eventObj2 = document.createEvent("Events"); eventObj2.initEvent('keyup', true, true); eventObj2.keyCode = 16; window.dispatchEvent(eventObj2);
                        }
                    }
                },wavySpeed/2)
                if (wavy != 3) {
                    eventObj2 = document.createEvent("Events"); eventObj2.initEvent('keyup', true, true); eventObj2.keyCode = 32; window.dispatchEvent(eventObj2);
                }
                if (wavy == 1 || wavy == 3) {
                    eventObj2 = document.createEvent("Events"); eventObj2.initEvent('keydown', true, true); eventObj2.keyCode = 16; window.dispatchEvent(eventObj2);
                }
            }
            wavyInt();
        },wavySpeed)
    }
    wavyInt();
    function setTO(i,key,rkey) {
        setTimeout(function() {
            eventObj1 = document.createEvent("Events"); eventObj1.initEvent('keydown', true, true); eventObj1.keyCode = key-(rkey-i); window.dispatchEvent(eventObj1);
            eventObj1 = document.createEvent("Events"); eventObj1.initEvent('keyup', true, true); eventObj1.keyCode = key-(rkey-i); window.dispatchEvent(eventObj1);
            setTimeout(function() {
                if (i < rkey) {
                    eventObj1 = document.createEvent("Events"); eventObj1.initEvent('keydown', true, true); eventObj1.keyCode = 69; window.dispatchEvent(eventObj1);
                    eventObj1 = document.createEvent("Events"); eventObj1.initEvent('keyup', true, true); eventObj1.keyCode = 69; window.dispatchEvent(eventObj1);
                } else {
                    eventObj1 = document.createEvent("Events"); eventObj1.initEvent('keydown', true, true); eventObj1.keyCode = 27; window.dispatchEvent(eventObj1);
                    eventObj1 = document.createEvent("Events"); eventObj1.initEvent('keyup', true, true); eventObj1.keyCode = 27; window.dispatchEvent(eventObj1);
                    oktoggle = true;
                }
            },stepTime)
        },i*stepTime*2)
    }
    function toggleSA(key) {
        var rkey = key-48;
        eventObj1 = document.createEvent("Events"); eventObj1.initEvent('keydown', true, true); eventObj1.keyCode = 27; window.dispatchEvent(eventObj1);
        eventObj1 = document.createEvent("Events"); eventObj1.initEvent('keyup', true, true); eventObj1.keyCode = 27; window.dispatchEvent(eventObj1);
        setTimeout(function(){
            eventObj1 = document.createEvent("Events"); eventObj1.initEvent('keydown', true, true); eventObj1.keyCode = 69; window.dispatchEvent(eventObj1);
            eventObj1 = document.createEvent("Events"); eventObj1.initEvent('keyup', true, true); eventObj1.keyCode = 69; window.dispatchEvent(eventObj1);
            for (var i = 1; i <= rkey; i++) {
                setTO(i,key,rkey);
            }
        },stepTime)
    }
    setInterval(function() {
        if (!!document.getElementById("canvas") && document.getElementById("canvas").width != Math.floor(1440/810*document.getElementById("canvas").height) && widest=="true") {
            document.getElementById("canvas").width = 1440/810*document.getElementById("canvas").height
        }
    },0)
})


