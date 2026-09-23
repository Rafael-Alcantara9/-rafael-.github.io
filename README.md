<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Perfil Profissional</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <style>
        .titulo-secao {
            font-size: 1.5rem;
            font-weight: 700;
            text-decoration: underline;
        }
    </style>
  
</head>

<body>

<header>
    <h1 class="text-3xl font-bold underline">
        Rafael Johnsons de Alcântara
    </h1>
    <p>Estudante de Desenvolvimento Web</p>
</header>

<main class="max-w-6xl mx-auto p-4">

    <section>
        

        <figure>
            <img src="perfil.png" alt="Foto de perfil profissional" width="200">
            <figcaption>Foto de perfil profissional</figcaption>
        </figure>

    </section>

    <section>
        <h2 class="titulo-secao">Habilidades</h2>

        <div class="grid grid-cols-1 md:grid-cols-1 gap-2">
            <div>HTML</div>
            <div>Banco de Dados</div>
</div> 
    </section>

    <section>
        <h2 class="text-2xl font-bold underline">Formação Acadêmica</h2>

        <table class="border-collapse border border-gray-400">

           

            <thead>
                <tr>
                    <th class="border border-gray-400 px-2 py-1" scope="col">Curso</th>
                    <th class="border border-gray-400 px-2 py-1" scope="col">Instituição</th>
                    <th class="border border-gray-400 px-2 py-1" scope="col">Ano</th>
                </tr>
            </thead>

            <tbody>
                <tr>
                    <td class="border border-gray-400 px-2 py-1" scope="col">Gestão da Tecnologia da Informação</td>
                    <td class="border border-gray-400 px-2 py-1" scope="col">FACULDADE SENAC</td>
                    <td class="border border-gray-400 px-2 py-1" scope="col">2022</td>
                </tr>

                <tr>
                    <td class="border border-gray-400 px-2 py-1" scope="col">Análise e Desenvolvimento de Sistemas</td>
                    <td class="border border-gray-400 px-2 py-1" scope="col">IFPE</td>
                    <td class="border border-gray-400 px-2 py-1" scope="col">2026</td>
                </tr>
            </tbody>

        </table>
    </section>

</main>

<footer>
    <p>Perfil Profissional - 2026</p>
</footer>


</body>

</html>
