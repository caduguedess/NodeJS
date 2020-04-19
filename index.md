<!DOCTYPE html>
<html>
    <head>
        <title>JavaScript Coordenadas Mouse</title>
    </head>
    <body>
        <p>Passe o mouse pela tela para saber as coordenadas do ponteiro</p>

        <p id="position"></p>
        <script>
            let el = document.getElementById("position");
            document.addEventListener("mousemove", function(e) {
                el.innerHTML = "As coordenadas do ponteiro do mouse sao " + e.pageX + " " + e.pageY;
            });
        </script>
    </body>
</html>