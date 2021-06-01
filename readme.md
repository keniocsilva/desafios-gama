https://github.com/keniocsilva/desafios-gama.git


<!DOCTYPE HTML>
<html lang="pt-br">

<head>
    <meta charset="utf-8">
    <title>Formulario em HTML</title>
</head>

<body>

    <h1>Formulario HTML</h1>
    <form name="formContato" action="" method="get" method="POST" action="form.php">

        <p>
        Nome: <br><input type="text" name="nome" required><br>
                
        </p>

        <p>
        Sobrenome: <br><input type="text" name="sobrenome" required><br>
        </p>

        <p>
        CPF:<br><label for="cpf"></label>
            <input type="text" name="cpf" size="11" maxlength="14" id="cpf" required><br>
        
        </p>

        <p>
        RG: <br><label for="rg"></label>
            <input type="text" name="rg" id="rg" required><br>
        
        </p>

        <p>
        Data de nascimento: <br><input type="date" name="date"><br>
        </p>

        <p>

            <br>Sexo:<br>
                <p></p>
                <input type="radio" name="sexo" value="masculino" id="masculino" checked>
                <label for="masculino">Masculino</label>
                <input type="radio" name="sexo" value="feminino" id="feminino"checked>
                <label for="feminino">Feminino</label>

               
           
        </p>

        <p>
            E-mail: <br><input type="email" name="email"><br>

        </p>

        <p>

            Endereço:<br><input type="text" name="endereco"><br>

        </p>

        <p>

            Numero: <br><input type="text" real="numero" id="numero"><br>

        </p>

        <p>
            Bairro:<br><input type="text" name="bairro"><br>
        </p>

        <p>
            Cidade:<br><input type="text" name="cidade"><br>
        </p>

        <p>
            Estado:<br><input type="text" name="estado" size="2" maxlength="2"><br>

        </p>

        <p>
            Cep:<br><input type="text" real="numero" id="cep"><br>
        </p>

        <p>

            Telefone Fixo: <br>DDD: <input type="text" real="numero" id="cod cidade" size="2" maxlength="2">
            | Telefone: <input type="text" real="numero" id="telefone fixo" size="8" maxlength="8"><br>
        </p>

        <p>

            Telefone Celular: <br>DDD: <input type="text" real="numero" id="cod cidade" size="2" maxlength="2">
            | Celular: <input type="text" real="numero" id="telefone fixo" size="9" maxlength="9"><br>
        </p>

        









    </form>
</body>