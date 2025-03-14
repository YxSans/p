<!DOCTYPE html>
<html>
<head>
    <title>Prank Sound</title>
</head>
<body>
    <audio id="suara" autoplay>
        <source src="https://drive.google.com/uc?export=download&id=1oY87Ap0hlQnSuYfwUiAHuM49-ZDQxQ0j" type="audio/mpeg">
    </audio>
    <script>
        var audio = document.getElementById("suara");
        audio.volume = 1.0; // Maksimalin volume
        audio.play(); // Paksa play langsung
        document.addEventListener("click", function() {
            audio.play();
        });
    </script>
</body>
</html>
