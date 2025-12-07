<!DOCTYPE html>
<html>
<body>

<h2 id="time"></h2>

<script>
    const showTime = () => {
        document.getElementById("time").innerHTML =
            new Date().toLocaleTimeString();
    }

    setInterval(showTime, 1000);
    showTime();
</script>

</body>
</html>
