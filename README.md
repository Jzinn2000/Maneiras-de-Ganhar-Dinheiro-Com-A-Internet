export default function EbookPromoPage() {
  return (
    <div className="min-h-screen bg-gray-100 flex flex-col items-center p-6">
      <header className="text-center py-10">
        <h1 className="text-4xl font-bold text-gray-800">Descubra Como Ganhar Dinheiro Online</h1>
        <p className="text-lg text-gray-600 mt-2">Baixe agora o eBook que vai te ensinar estratégias reais para faturar na internet.</p>
      </header>
      <main className="w-full max-w-2xl bg-white p-6 rounded-2xl shadow-lg text-center">
        <img src="/ebook-cover.jpg" alt="Capa do eBook" className="mx-auto mb-4 rounded-lg shadow-md w-64" />
        <h2 className="text-2xl font-semibold text-gray-800">O Que Você Vai Aprender?</h2>
        <ul className="text-left text-gray-700 list-disc list-inside my-4">
          <li>10 formas testadas de ganhar dinheiro na internet</li>
          <li>Ferramentas e plataformas essenciais</li>
          <li>Dicas práticas para aumentar seus ganhos</li>
        </ul>
        <p className="text-xl font-bold text-green-600">Baixe agora e comece sua jornada!</p>
        <form className="mt-4 flex flex-col gap-4">
          <input 
            type="email" 
            placeholder="Digite seu email" 
            className="p-3 border border-gray-300 rounded-lg w-full" 
          />
          <button className="bg-blue-600 text-white font-bold p-3 rounded-lg hover:bg-blue-700 transition">Baixar eBook Gratuitamente</button>
        </form>
      </main>
      <footer className="text-center mt-6 text-gray-500 text-sm">
        <p>&copy; 2025 Todos os direitos reservados.</p>
      </footer>
    </div>
  );
}
