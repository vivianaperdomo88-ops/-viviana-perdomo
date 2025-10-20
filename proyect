        import React, { useState } from "react";
import {
  FileText,
  Users,
  Calendar,
  DollarSign,
  CheckCircle,
  Target,
  BarChart,
  ChevronDown,
  ChevronUp,
  Briefcase,
  BookOpen,
  Award,
} from "lucide-react";

const PropuestaEvaluacion = () => {
  const [propuestaActiva, setPropuestaActiva] = useState(1);
  const [seccionExpandida, setSeccionExpandida] = useState(null);

  const toggleSeccion = (seccion) => {
    setSeccionExpandida(seccionExpandida === seccion ? null : seccion);
  };

  // ================================
  // PROPUESTA TÉCNICA
  // ================================
  const propuesta1 = {
    metodologia: {
      titulo: "Metodología de Evaluación",
      items: [
        {
          fase: "Fase 1: Alistamiento",
          duracion: "2 semanas",
          actividades:
            "Revisión documental, diseño de instrumentos, coordinación logística y plan operativo.",
        },
        {
          fase: "Fase 2: Recolección de información",
          duracion: "3 semanas",
          actividades:
            "Entrevistas semiestructuradas, grupos focales, encuestas y trabajo de campo.",
        },
        {
          fase: "Fase 3: Análisis y sistematización",
          duracion: "2 semanas",
          actividades:
            "Análisis cualitativo y cuantitativo, triangulación y validación de hallazgos.",
        },
        {
          fase: "Fase 4: Informe final",
          duracion: "1 semana",
          actividades:
            "Elaboración de informe final, recomendaciones y socialización de resultados.",
        },
      ],
    },

    tecnicas: [
      {
        nombre: "Entrevistas semiestructuradas",
        cantidad: "20",
        target: "Actores clave, beneficiarios y aliados institucionales",
      },
      {
        nombre: "Grupos focales",
        cantidad: "6",
        target: "Representantes de población LGBTIQ+ y aliados",
      },
      {
        nombre: "Encuestas digitales",
        cantidad: "80",
        target: "Participantes del proyecto en diferentes municipios",
      },
      {
        nombre: "Revisión documental",
        cantidad: "Total",
        target: "Informes técnicos, planes operativos y reportes de ejecución",
      },
    ],

    criterios: [
      {
        nombre: "Pertinencia",
        peso: "20%",
        descripcion: "Alineación con necesidades del contexto y los objetivos del proyecto.",
      },
      {
        nombre: "Eficacia",
        peso: "20%",
        descripcion: "Cumplimiento de metas y resultados esperados.",
      },
      {
        nombre: "Eficiencia",
        peso: "15%",
        descripcion: "Uso adecuado de recursos financieros y humanos.",
      },
      {
        nombre: "Impacto",
        peso: "20%",
        descripcion: "Cambios positivos observables en los beneficiarios y comunidades.",
      },
      {
        nombre: "Sostenibilidad",
        peso: "15%",
        descripcion: "Capacidad de continuidad de resultados una vez finalizado el apoyo.",
      },
      {
        nombre: "Enfoque de género y diversidad",
        peso: "10%",
        descripcion: "Inclusión transversal del enfoque de derechos humanos e identidad.",
      },
    ],

    productos: [
      { entregable: "Plan operativo y metodología", fecha: "Semana 2" },
      { entregable: "Informe preliminar", fecha: "Semana 6" },
      { entregable: "Informe final + anexos", fecha: "Semana 8" },
      { entregable: "Presentación pública de resultados", fecha: "Semana 8" },
    ],
  };

  // ================================
  // PROPUESTA FINANCIERA
  // ================================
  const propuesta2 = {
    presupuestoTotal: "$25.000.000 COP",
    distribucion: [
      { concepto: "Honorarios del equipo evaluador", monto: "$13.000.000", porcentaje: "52%" },
      { concepto: "Trabajo de campo y viáticos", monto: "$4.200.000", porcentaje: "17%" },
      { concepto: "Materiales y herramientas", monto: "$2.000.000", porcentaje: "8%" },
      { concepto: "Análisis de datos y software", monto: "$1.500.000", porcentaje: "6%" },
      { concepto: "Producción y socialización de informes", monto: "$1.300.000", porcentaje: "5%" },
      { concepto: "Imprevistos y gestión administrativa", monto: "$3.000.000", porcentaje: "12%" },
    ],
    cronograma: [
      { mes: "Mes 1", semanas: "1-2", actividad: "Alistamiento", pago: "30%", monto: "$7.500.000" },
      { mes: "Mes 1", semanas: "3-4", actividad: "Recolección de datos", pago: "25%", monto: "$6.250.000" },
      { mes: "Mes 2", semanas: "5-6", actividad: "Análisis y sistematización", pago: "25%", monto: "$6.250.000" },
      { mes: "Mes 2", semanas: "7-8", actividad: "Informe final y socialización", pago: "20%", monto: "$5.000.000" },
    ],
  };

  // ================================
  // HOJA DE VIDA
  // ================================
  const hojaDeVida = {
    nombre: "Alied Viviana Perdomo Payán",
    profesion: "Politóloga - Universidad del Tolima",
    perfil:
      "Profesional en Ciencia Política con experiencia en formulación y evaluación de proyectos sociales, monitoreo, análisis de políticas públicas y construcción de líneas base. Enfoque en derechos humanos, diversidad sexual, género y paz territorial.",
    experiencia: [
      {
        cargo: "Auxiliar Técnica - Contraloría Municipal de Ibagué",
        descripcion:
          "Apoyo en control fiscal, revisión documental y elaboración de informes técnicos de gestión.",
      },
      {
        cargo: "Investigadora - Universidad del Tolima",
        descripcion:
          "Diseño metodológico de línea base sobre trabajo infantil y análisis de información cuantitativa y cualitativa.",
      },
      {
        cargo: "Consultora Independiente",
        descripcion:
          "Asesorías en evaluación de proyectos, políticas públicas y programas sociales con enfoque de derechos humanos.",
      },
    ],
    habilidades: [
      "Evaluación de proyectos sociales",
      "Diseño de metodologías participativas",
      "Análisis cuantitativo y cualitativo",
      "Excel y Power BI (avanzado)",
      "Gestión por resultados (GpRD)",
      "Canva y redacción técnica profesional",
    ],
    idiomas: ["Español (nativo)", "Inglés (intermedio - lectura técnica)"],
  };

  return (
    <div className="min-h-screen bg-gradient-to-br from-purple-50 via-pink-50 to-blue-50 p-6">
      <div className="max-w-6xl mx-auto">
        {/* ENCABEZADO */}
        <div className="bg-white rounded-2xl shadow-xl p-8 mb-6 border-t-4 border-purple-600">
          <h1 className="text-3xl font-bold text-gray-800 mb-2">Propuestas Técnicas y Financieras</h1>
          <p className="text-gray-600">
            Evaluación Final del Proyecto “Derechos Humanos LGBTIQ+ y Empleo” – AEXCID / Caribe Afirmativo
          </p>
        </div>

        {/* SELECTOR */}
        <div className="flex flex-col md:flex-row gap-4 mb-6">
          <button
            onClick={() => setPropuestaActiva(1)}
            className={`flex-1 py-4 rounded-xl font-semibold transition-all ${
              propuestaActiva === 1
                ? "bg-gradient-to-r from-purple-600 to-pink-600 text-white shadow-lg transform scale-105"
                : "bg-white text-gray-700 hover:bg-gray-50"
            }`}
          >
            📋 Propuesta Técnica
          </button>
          <button
            onClick={() => setPropuestaActiva(2)}
            className={`flex-1 py-4 rounded-xl font-semibold transition-all ${
              propuestaActiva === 2
                ? "bg-gradient-to-r from-purple-600 to-pink-600 text-white shadow-lg transform scale-105"
                : "bg-white text-gray-700 hover:bg-gray-50"
            }`}
          >
            💰 Propuesta Financiera
          </button>
          <button
            onClick={() => setPropuestaActiva(3)}
            className={`flex-1 py-4 rounded-xl font-semibold transition-all ${
              propuestaActiva === 3
                ? "bg-gradient-to-r from-purple-600 to-pink-600 text-white shadow-lg transform scale-105"
                : "bg-white text-gray-700 hover:bg-gray-50"
            }`}
          >
            👩‍💼 Hoja de Vida
          </button>
        </div>

        {/* ====================== PROPUESTA TÉCNICA ====================== */}
        {propuestaActiva === 1 && (
          <div className="space-y-6">
            {/* METODOLOGÍA */}
            <div className="bg-white rounded-xl shadow-lg p-6">
              <div
                className="flex items-center justify-between cursor-pointer"
                onClick={() => toggleSeccion("metodologia")}
              >
                <h2 className="text-2xl font-bold text-purple-700 flex items-center gap-3">
                  <BarChart className="w-6 h-6" /> {propuesta1.metodologia.titulo}
                </h2>
                {seccionExpandida === "metodologia" ? <ChevronUp /> : <ChevronDown />}
              </div>

              {seccionExpandida === "metodologia" && (
                <div className="mt-6 space-y-4">
                  {propuesta1.metodologia.items.map((fase, idx) => (
                    <div
                      key={idx}
                      className="flex gap-4 p-4 bg-gradient-to-r from-purple-50 to-pink-50 rounded-lg"
                    >
                      <div className="flex-shrink-0 w-12 h-12 bg-purple-600 text-white rounded-full flex items-center justify-center font-bold">
                        {idx + 1}
                      </div>
                      <div className="flex-1">
                        <h3 className="font-bold text-gray-800">{fase.fase}</h3>
                        <p className="text-sm text-purple-600 font-semibold">{fase.duracion}</p>
                        <p className="text-gray-600 mt-1">{fase.actividades}</p>
                      </div>
                    </div>
                  ))}
                </div>
              )}
            </div>

            {/* CRITERIOS */}
            <div className="bg-white rounded-xl shadow-lg p-6">
              <h2 className="text-2xl font-bold text-blue-700 mb-6 flex items-center gap-3">
                <CheckCircle className="w-6 h-6" /> Criterios de Evaluación
              </h2>
              <div className="space-y-3">
                {propuesta1.criterios.map((criterio, idx) => (
                  <div key={idx} className="flex items-center gap-4 p-4 bg-blue-50 rounded-lg">
                    <div className="flex-shrink-0 w-16 h-16 bg-blue-600 text-white rounded-lg flex items-center justify-center font-bold text-xl">
                      {criterio.peso}
                    </div>
                    <div className="flex-1">
                      <h3 className="font-bold text-gray-800">{criterio.nombre}</h3>
                      <p className="text-sm text-gray-600">{criterio.descripcion}</p>
                    </div>
                  </div>
                ))}
              </div>
            </div>
          </div>
        )}

        {/* ====================== PROPUESTA FINANCIERA ====================== */}
        {propuestaActiva === 2 && (
          <div className="space-y-6">
            <div className="bg-white rounded-xl shadow-lg p-6">
              <h2 className="text-2xl font-bold text-purple-700 mb-6 flex items-center gap-3">
                <DollarSign className="w-6 h-6" /> Distribución Presupuestal
              </h2>
              <div className="space-y-3">
                {propuesta2.distribucion.map((item, idx) => (
                  <div
                    key={idx}
                    className="flex items-center justify-between p-4 bg-gradient-to-r from-purple-50 to-pink-50 rounded-lg"
                  >
                    <div className="flex-1">
                      <h3 className="font-semibold text-gray-800">{item.concepto}</h3>
                    </div>
                    <div className="text-right">
                      <p className="font-bold text-xl text-purple-700">{item.monto}</p>
                      <p className="text-sm text-gray-600">{item.porcentaje}</p>
                    </div>
                  </div>
                ))}
              </div>
              <div className="mt-6 p-6 bg-gradient-to-r from-purple-600 to-pink-600 rounded-lg text-white">
                <div className="flex justify-between items-center">
                  <span className="text-xl font-semibold">TOTAL PRESUPUESTO</span>
                  <span className="text-3xl font-bold">{propuesta2.presupuestoTotal}</span>
                </div>
              </div>
            </div>
          </div>
        )}

        {/* ====================== HOJA DE VIDA ====================== */}
        {propuestaActiva === 3 && (
          <div className="bg-white rounded-xl shadow-lg p-8">
            <h2 className="text-3xl font-bold text-purple-700 mb-6">
              👩‍💼 Hoja de Vida – {hojaDeVida.nombre}
            </h2>
            <p className="text-gray-700 mb-4">{hojaDeVida.perfil}</p>

            <div className="mt-6">
              <h3 className="text-xl font-semibold text-pink-700 mb-2">
                <Briefcase className="inline w-5 h-5 mr-2" /> Experiencia Laboral
              </h3>
              <ul className="list-disc ml-6 text-gray-700 space-y-2">
                {hojaDeVida.experiencia.map((exp, idx) => (
                  <li key={idx}>
                    <strong>{exp.cargo}:</strong> {exp.descripcion}
                  </li>
                ))}
              </ul>
            </div>

            <div className="mt-6">
              <h3 className="text-xl font-semibold text-blue-700 mb-2">
                <BookOpen className="inline w-5 h-5 mr-2" /> Formación y Habilidades
              </h3>
              <ul className="list-disc ml-6 text-gray-700 space-y-2">
                {hojaDeVida.habilidades.map((hab, idx) => (
                  <li key={idx}>{hab}</li>
                ))}
              </ul>
            </div>

            <div className="mt-6">
              <h3 className="text-xl font-semibold text-green-700 mb-2">
                <Award className="inline w-5 h-5 mr-2" /> Idiomas
              </h3>
              <ul className="list-disc ml-6 text-gray-700 space-y-2">
                {hojaDeVida.idiomas.map((idioma, idx) => (
                  <li key={idx}>{idioma}</li>
                ))}
              </ul>
            </div>
          </div>
        )}
      </div>
    </div>
  );
};

export default PropuestaEvaluacion;
