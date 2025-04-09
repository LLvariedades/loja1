<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>L e L Variedades</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            primario: '#3ABEFF', // azul claro
          }
        }
      }
    }
  </script>
</head>
<body class="bg-primario text-white font-sans min-h-screen">

  <header class="bg-white text-primario p-4 shadow-md">
    <h1 class="text-3xl font-bold text-center">L e L Variedades</h1>
  </header>

  <main class="p-6 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
    <!-- Produto exemplo 1 -->
    <div class="bg-white text-black rounded-2xl shadow-lg p-4">
      <img src="https://via.placeholder.com/300x200" alt="Produto 1" class="rounded-xl w-full h-48 object-cover mb-4">
      <h2 class="text-xl font-semibold mb-2">Produto Exemplo 1</h2>
      <p class="mb-2">Descrição breve do produto.</p>
      <span class="font-bold text-primario">R$ 49,99</span>
    </div>

    <!-- Produto exemplo 2 -->
    <div class="bg-white text-black rounded-2xl shadow-lg p-4">
      <img src="https://via.placeholder.com/300x200" alt="Produto 2" class="rounded-xl w-full h-48 object-cover mb-4">
      <h2 class="text-xl font-semibold mb-2">Produto Exemplo 2</h2>
      <p class="mb-2">Outro produto legal com boa descrição.</p>
      <span class="font-bold text-primario">R$ 29,90</span>
    </div>

    <!-- Adicione mais produtos aqui seguindo o mesmo padrão -->
  </main>

  <footer class="bg-white text-center text-primario p-4 mt-8">
    &copy; 2025 L e L Variedades. Todos os direitos reservados.
  </footer>

</body>
</html>
