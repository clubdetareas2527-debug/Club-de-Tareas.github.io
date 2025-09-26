# Club-de-Tareas.github.io
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Servicios Sociales Registro</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      padding: 20px;
    }

    h1 {
      color: #0d6efd;
    }

    .blue-row {
      background-color: #cce5ff;
    }

    .pink-row {
      background-color: #f8d7da;
    }

    .red-row {
      background-color: #f5c6cb;
    }

    .imagen {
      max-width: 100%;
      height: auto;
      border: 2px solid #333;
      border-radius: 10px;
      margin-top: 20px;
    }

    input[type="file"] {
      margin-top: 20px;
      padding: 10px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    input[type="file"]:hover {
      background-color: #45a049;
    }

    textarea {
      width: 95%;
      height: 120px;
      resize: vertical;
    }

    .timer {
      font-size: 14px;
      font-weight: bold;
      color: #d63384;
    }
  </style>
</head>
<body>

  <h1>¡Bienvenidas/dos al registro de club de tareas!</h1>

    <div class="mb-3">
      <label for="email" class="form-label">Añade una cuenta Gmail y/o Email</label>
      <input type="email" class="form-control" id="email" name="email" placeholder="name@example.com">
    </div>

    <div class="mb-3">
      <label for="nombreCompleto" class="form-label">Nombre completo</label>
      <input type="text" class="form-control" id="nombreCompleto" name="nombreCompleto" placeholder="Escribe tu nombre completo">
    </div>

    <div class="mb-3">
      <label for="nombreBiblioteca" class="form-label">Nombre de la biblioteca</label>
      <select class="form-select" id="nombreBiblioteca" name="nombreBiblioteca">
        <option value="" selected>Selecciona una biblioteca</option>
        <option value="José Luis Álamo Jardón">José Luis Álamo Jardón</option>
        <option value="Rafael Moreno Montes de Oca">Rafael Moreno Montes de Oca</option>
        <option value="Guillermina Nateras López">Guillermina Nateras López</option>
        <option value="San Pedro Totoltepec">San Pedro Totoltepec</option>
        <option value="Dr. Urban Boutelegier">Dr. Urban Boutelegier</option>
        <option value="Michel D’Hooghe">Michel D’Hooghe</option>
        <option value="Santa Teresita del Niño Jesús">Santa Teresita del Niño Jesús</option>
        <option value="Biblioteca Santiago Tlacotepec">Biblioteca Santiago Tlacotepec</option>
        <option value="Biblioteca Santiago Tlaxomulco">Biblioteca Santiago Tlaxomulco</option>
        <option value="Biblioteca Tecaxic">Biblioteca Tecaxic</option>
        <option value="Ludoteca San Cristóbal Huichochitlán">Ludoteca San Cristóbal Huichochitlán</option>
        <option value="Museo Municipal de Calixtlahuaca">Museo Municipal de Calixtlahuaca</option>
        <option value="Museo del Alfeñique">Museo del Alfeñique</option>
        <option value="Lic. Jaime Almazán Delgado">Lic. Jaime Almazán Delgado</option>
        <option value="José María Heredia y Heredia">José María Heredia y Heredia</option>
        <option value="Leonardo Sánchez Montaño">Leonardo Sánchez Montaño</option>
        <option value="Otomitl">Otomitl</option>
        <option value="Concepción García Valdez">Concepción García Valdez</option>
        <option value="Sor Juana Inés de la Cruz">Sor Juana Inés de la Cruz</option>
        <option value="Mercedes López Gómeztagle">Mercedes López Gómeztagle</option>
        <option value="Edelmira Nava Arellano">Edelmira Nava Arellano</option>
        <option value="Profa. Laura Beatriz Benavides">Profa. Laura Beatriz Benavides</option>
        <option value="Agustín María Lebrija">Agustín María Lebrija</option>
        <option value="Rodolfo García Gutiérrez">Rodolfo García Gutiérrez</option>
        <option value="Laura Méndez de Cuenca">Laura Méndez de Cuenca</option>
        <option value="Mercedes Carrasco">Mercedes Carrasco</option>
        <option value="Fray Andrés de Castro">Fray Andrés de Castro</option>
      </select>
    </div>

    
    <div class="mb-3">
      <label for="coberturaAtencion" class="form-label">Cobertura de atención / Delegación</label>
      <select class="form-select" id="coberturaAtencion" name="coberturaAtencion">
        <option value="" selected>Selecciona la delegación o cobertura</option>
        <option value="San Lorenzo Tepaltitlán">San Lorenzo Tepaltitlán</option>
        <option value="Santa Cruz Atzcapotzaltongo">Santa Cruz Atzcapotzaltongo</option>
        <option value="San Mateo Oxtotitlán, Nueva Oxtotitlán">San Mateo Oxtotitlán, Nueva Oxtotitlán</option>
        <option value="San Pedro Totoltepec">San Pedro Totoltepec</option>
        <option value="San Diego de los Padres Cuexcontitlán">San Diego de los Padres Cuexcontitlán</option>
        <option value="San Cayetano Morelos">San Cayetano Morelos</option>
        <option value="Morelos, Sánchez">Morelos, Sánchez</option>
        <option value="Santiago Tlacotepec, San Juan Tilapa">Santiago Tlacotepec, San Juan Tilapa</option>
        <option value="Santiago Tlaxomulco">Santiago Tlaxomulco</option>
        <option value="Tecaxic">Tecaxic</option>
        <option value="San Cristóbal Huichochitlán">San Cristóbal Huichochitlán</option>
        <option value="Toluca, Estado de México, México y extranjero">Toluca, Estado de México, México y extranjero</option>
        <option value="La Maquinita, Santiago Miltepec">La Maquinita, Santiago Miltepec</option>
        <option value="Cacalomacán">Cacalomacán</option>
        <option value="San Mateo Otzacatipan">San Mateo Otzacatipan</option>
        <option value="Tlachaloya">Tlachaloya</option>
        <option value="San Martín Toltepec">San Martín Toltepec</option>
        <option value="Independencia">Independencia</option>
        <option value="Capultitlán, Moderna de la Cruz">Capultitlán, Moderna de la Cruz</option>
        <option value="San Andrés Cuexcontitlán">San Andrés Cuexcontitlán</option>
        <option value="San Antonio Buenavista, San Buenaventura">San Antonio Buenavista, San Buenaventura</option>
        <option value="San Pablo Autopan">San Pablo Autopan</option>
        <option value="Seminario Conciliar, Seminario 2 de marzo, Seminario las Torres, Felipe Chávez Becerril">Seminario Conciliar, Seminario 2 de marzo, Seminario las Torres, Felipe Chávez Becerril</option>
        <option value="Calixtlahuaca, San Marcos Yachihuacaltepec">Calixtlahuaca, San Marcos Yachihuacaltepec</option>
      </select>
    </div>
    <h2 style="text-align:center;">Plan de Octubre - Noviembre 2025</h2>
  <table class="table table-bordered">
   <!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contador de Tiempo</title>
</head>
<body>
  <form class="form register"
      action="https://formspree.io/f/xldpdare"
    method="POST"
    >
<table border="1">
  <thead>
    <tr>
      <th>Semana</th>
      <th>Tarea</th>
      <th>Fecha de Entrega</th>
      <th>No. de Asistentes</th>
      <th>Nota Informativa</th>
      <th>Archivos</th>
    </tr>
  </thead>
  <tbody>
  <html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Tabla de Actividades</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
            font-family: Arial, sans-serif;
        }
        th, td {
            border: 1px solid #ccc;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2ff;
            text-align: center;
        }
        .header-green {
            background-color: #d9ead3; /* Color verde claro similar al de la imagen */
        }
        .celda-verde {
            background-color: #d9ead3;
            text-align: center;
        }
        textarea {
            width: 100%;
            min-height: 50px;
            box-sizing: border-box;
        }
        /* Estilos básicos para el botón Entregar, similar a "btn btn-primary" de Bootstrap */
        .btn-primary {
            background-color: #007bff;
            color: white;
            border: none;
            padding: 5px 10px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            cursor: pointer;
            border-radius: 4px;
        }
    </style>
</head>
<body>

<table>
    <thead>
        <tr>
            <th rowspan="2">SEMANA</th>
            <th rowspan="2">TEMA</th>
            <th colspan="2">OCTUBRE 2025</th>
            <th colspan="2">NOVIEMBRE 2025</th>
            <th rowspan="2">Asistencia</th>
            <th rowspan="2">Nota Informativa</th>
            <th rowspan="2">Temporizador</th>
            <th rowspan="2">Evidencia</th>
            <th rowspan="2">Acción</th>
        </tr>
        <tr>
            <th>MIÉRCOLES</th>
            <th>JUEVES</th>
            <th>MIÉRCOLES</th>
            <th>JUEVES</th>
        </tr>
    </thead>
    <tbody>

    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td rowspan="2">1</td>
            <td>Día Mundial de la Alimentación</td>
            <td class="celda-verde">16</td>
            <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-10-16T23:59:59"></span>
            </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Día Mundial de la Alimentación">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Semáforo de la alimentación</td>
            <td class="celda-verde"></td> <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-10-16T23:59:59"></span>
            </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Semáforo de la alimentación">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>

    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td rowspan="3">2</td>
            <td>Celebración del día de Muertos</td>
            <td class="celda-verde">22</td>
            <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-10-22T23:59:59"></span>
            </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Celebración del día de Muertos">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Papel picado</td>
            <td></td>
            <td class="celda-verde">23</td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-10-23T23:59:59"></span>
            </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Papel picado">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>La Ofrenda</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-10-23T23:59:59"></span> </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="La Ofrenda">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>


    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td rowspan="5">3</td>
            <td>Flor de cempasúchil</td>
            <td class="celda-verde"></td>
            <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-10-23T23:59:59"></span> </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Flor de cempasúchil">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Calaveras Literarias</td>
            <td class="celda-verde">29</td>
            <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-10-29T23:59:59"></span>
            </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Calaveras Literarias">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Versos escritos</td>
            <td></td>
            <td class="celda-verde"></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-10-29T23:59:59"></span> </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Versos escritos">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>José Guadalupe Posada</td>
            <td></td>
            <td class="celda-verde">30</td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-10-30T23:59:59"></span>
            </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="José Guadalupe Posada">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Sopa de letras</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-10-30T23:59:59"></span> </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Sopa de letras">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>

    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td rowspan="4">4</td>
            <td>Revolución Mexicana</td>
            <td></td>
            <td></td>
            <td class="celda-verde">5</td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-05T23:59:59"></span>
            </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Revolución Mexicana">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Rompecabezas</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-05T23:59:59"></span> </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Rompecabezas">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Sor Juana Inés de la Cruz</td>
            <td></td>
            <td></td>
            <td></td>
            <td class="celda-verde">6</td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-06T23:59:59"></span>
            </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Sor Juana Inés de la Cruz">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Mandala</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-06T23:59:59"></span> </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Mandala">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>


    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td rowspan="4">5</td>
            <td>Principales líderes de la revolución</td>
            <td></td>
            <td></td>
            <td class="celda-verde">12</td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-12T23:59:59"></span>
            </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Principales líderes de la revolución">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Crucigrama</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-12T23:59:59"></span> </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Crucigrama">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Mujeres de la revolución</td>
            <td></td>
            <td></td>
            <td></td>
            <td class="celda-verde">13</td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-13T23:59:59"></span>
            </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Mujeres de la revolución">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Cubo</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-13T23:59:59"></span> </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Cubo">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>


    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td rowspan="4">6</td>
            <td>Constitución de 1917</td>
            <td></td>
            <td></td>
            <td class="celda-verde">19</td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-19T23:59:59"></span>
            </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Constitución de 1917">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Venustiano Carranza armable</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-19T23:59:59"></span> </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Venustiano Carranza armable">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Día Internacional de la palabra</td>
            <td></td>
            <td></td>
            <td></td>
            <td class="celda-verde">20</td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-20T23:59:59"></span>
            </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Día Internacional de la palabra">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Leer un texto y comentarlo</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-20T23:59:59"></span> </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Leer un texto y comentarlo">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>


    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td rowspan="2">7</td>
            <td>Hablemos de nuestras emociones</td>
            <td></td>
            <td></td>
            <td class="celda-verde">26</td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-26T23:59:59"></span>
            </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Hablemos de nuestras emociones">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td>Termómetro de las emociones</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-26T23:59:59"></span> </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Termómetro de las emociones">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>

    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td></td> <td>Día internacional del jaguar</td>
            <td></td>
            <td></td>
            <td></td>
            <td class="celda-verde">27</td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-27T23:59:59"></span>
            </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Día internacional del jaguar">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>
    <form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
        <tr>
            <td></td> <td>Jaguar oscilatorio</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>
                <input type="checkbox" name="asistencia"> Asistió
            </td>
            <td>
                <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
            </td>
            <td>
                <span class="timer" data-fecha="2025-11-27T23:59:59"></span> </td>
            <td>
                <input type="file" name="evidencia" required>
            </td>
            <td>
                <input type="hidden" name="actividad" value="Jaguar oscilatorio">
                <button type="submit" class="btn btn-primary">Entregar</button>
            </td>
        </tr>
    </form>

    </tbody>
</table>

</body>
</html>
