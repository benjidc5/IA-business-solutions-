cd ia-business-solution
export default function Home() {
  return (
    <main className="p-4 md:p-10 bg-white text-gray-900">
      <section className="text-center py-10">
        <h1 className="text-4xl md:text-6xl font-bold mb-4">
          IA Business Solution
        </h1>
        <p className="text-xl max-w-2xl mx-auto">
          Consultoría de Inteligencia Artificial para negocios latinos y americanos en el DMV.
          Automatiza, innova y haz crecer tu empresa con IA personalizada.
        </p>
        <button className="mt-6 text-lg px-6 py-3 rounded-2xl shadow-lg bg-blue-600 text-white hover:bg-blue-700">
          Reserva tu consulta gratuita
        </button>
      </section>

      <section className="grid gap-8 md:grid-cols-2 py-12">
        <div className="border rounded-xl shadow-md p-6">
          <h2 className="text-2xl font-semibold mb-2">Chatbots con esencia de tu marca</h2>
          <p>
            Creamos asistentes virtuales que representan tu negocio, responden en dos idiomas y filtran clientes para ti.
          </p>
        </div>
        <div className="border rounded-xl shadow-md p-6">
          <h2 className="text-2xl font-semibold mb-2">Automatización inteligente</h2>
          <p>
            Optimiza tareas repetitivas como atención al cliente, reservas o inventarios, sin complicaciones técnicas.
          </p>
        </div>
        <div className="border rounded-xl shadow-md p-6">
          <h2 className="text-2xl font-semibold mb-2">Agencia de clonación de creadores</h2>
          <p>
            ¿Eres creador de contenido? Creamos tu clon digital con voz, video y estilo para escalar tu presencia online.
          </p>
        </div>
        <div className="border rounded-xl shadow-md p-6">
          <h2 className="text-2xl font-semibold mb-2">IA para decisiones de negocio</h2>
          <p>
            Usa IA para entender mejor a tus clientes, mejorar ventas y tomar decisiones basadas en datos.
          </p>
        </div>
      </section>

      <section className="py-12 bg-gray-100 rounded-xl px-6">
        <h2 className="text-3xl font-bold text-center mb-6">¿Cómo trabajamos?</h2>
        <ul className="max-w-3xl mx-auto space-y-4 text-lg">
          <li>✅ Diagnóstico gratuito del negocio</li>
          <li>✅ Propuesta personalizada de solución IA</li>
          <li>✅ Implementación paso a paso</li>
          <li>✅ Acompañamiento continuo y soporte</li>
        </ul>
      </section>

      <section className="py-10 text-center">
        <h2 className="text-3xl font-bold mb-4">¿Listo para transformar tu negocio?</h2>
        <p className="text-lg mb-6">
          Atendemos en inglés y español. Trabajamos con empresas en Maryland, DC y Virginia.
        </p>
        <button className="text-lg px-6 py-3 rounded-2xl shadow-lg bg-blue-600 text-white hover:bg-blue-700">
          Agenda tu asesoría gratuita
        </button>
      </section>

      <footer className="pt-10 text-center text-sm text-gray-500">
        <p>📍 Maryland, EE. UU. | 📞 +1 (240) 790 4685| 📧 info@iabusinesssolution.com</p>
        <p>&copy; 2025 IA Business Solution. Todos los derechos reservados.</p>
      </footer>
    </main>
  );
}
