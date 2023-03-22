# tabsh
tabela shahut
<!DOCTYPE html>
<html>

<head>
    <title>tabela e shahut</title>


</head>

<body>
    <script type="text/javascript">


        let table = document.createElement("table");//krijuam tabelen

        for (let i = 0; i < 10; i++) {
            let rreshti = document.createElement("tr"); //krijojme reshtin
            for (let j = 0; j < 10; j++) {
                let
                    qeliza = document.createElement("td"); //krijojme kolonen
                if ((i + j) % 2 == 0) {
                    qeliza.style.backgroundColor = "red";
                    qeliza.style.width = "100px";
                }
                else {
                    qeliza.style.backgroundColor = "black";
                    qeliza.style.width = "100px"
                }
                rreshti.appendChild(qeliza);
            }
            table.appendChild(rreshti);
        }

        document.body.appendChild(table);


    </Script>
</body>

</html>
