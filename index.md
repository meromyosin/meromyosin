[Music](https://music.youtube.com/channel/UCm3j63uK8LV3R7O0nvPiGNA)

[Movies I Like](https://gusmeadows.github.io/mvilike)

[BHacker](https://gusmeadows.github.io/bhacker)

[Players](https://gusmeadows.github.io/playerjs)

[Jwm config](https://gusmeadows.github.io/jwm)

[Github](https://github.com/gusmeadows)

[old github](https://github.com/olderaccount)

    
<button onclick="clicked()">if u like this site click here</button>

<script>
function clicked() {
    var xhr = new XMLHttpRequest();
    xhr.open("GET", "gusmeadows.github.io/awesomeclick");
    xhr.responseType = "json";
    xhr.onload = function() {
        alert(`${this.response.value} like this`);
    }
    xhr.send();
}
</script>

<div id="visits">... </div>

<script>
function cb(response) {
    document.getElementById('visits').innerText = response.value;
}
</script>
<script async src="https://api.countapi.xyz/hit/gusmeadows.github.io/visits?callback=cb"></script>
