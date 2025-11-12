---
title: Aplicación. Configurador de horarios para el alumnado de matemáticas de la USC
draft: false
date: "2025-09-05"
description: ""
tags: ["Novas", "MaEGA"]
authors:
  - "maega"
---
Con motivo del inicio de este curso 2025-2026 ponemos a disposición del alumnado de la facultad de matemáticas una herramienta para agilizar el habitualmente tedioso proceso de configurar el horario lectivo al comenzar un nuevo curso académico.

Mediante un formulario, el alumnado podrá seleccionar los grupos expositivos e interactivos de las asignaturas qeu esté cursando, pudiendo ser estas de diferentes cursos. Luego de enviar el formulario recibirá un correo notificándole que se le acaba de compartir vía Google Drive un fichero PDF con su horario personalizado.

<!-- <iframe
  src="https://forms.gle/TPJx94Dg6L1fUVgeA"
  height="620"
  width="569">
</iframe> -->

<div class="center-cbtn">
  <cbutton>Configura aquí tu horario!</cbutton>
</div>

<style>
.center-cbtn {
  display: flex;
  justify-content: center;
  margin: 2em 0;
}

cbutton {
 appearance: none;
 background-color: transparent;
 border: 0.125em solid #1A1A1A;
 border-radius: 0.9375em;
 box-sizing: border-box;
 color: #3B3B3B;
 cursor: pointer;
 display: inline-flex; /* Cambiado a inline-flex */
 align-items: center;  /* Centrado vertical */
 justify-content: center;
 font-size: 16px;
 font-weight: 600;
 line-height: normal;
 margin: 0;
 min-height: 3.75em;
 min-width: 0;
 outline: none;
 padding: .25em 1em;
 text-align: center;
 text-decoration: none;
 transition: all 300ms cubic-bezier(.23, 1, 0.32, 1);
 user-select: none;
 -webkit-user-select: none;
 touch-action: manipulation;
 will-change: transform;
}

cbutton:disabled {
 pointer-events: none;
}

cbutton:hover {
 color: #fff;
 background-color: #1A1A1A;
 box-shadow: rgba(0, 0, 0, 0.25) 0 8px 15px;
 transform: translateY(-2px);
}

cbutton:active {
 box-shadow: none;
 transform: translateY(0);
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const btn = document.querySelector('cbutton');
  if (btn) {
    btn.addEventListener('click', function() {
      window.open('https://forms.gle/TPJx94Dg6L1fUVgeA', '_blank');
    });
  }
});
</script>