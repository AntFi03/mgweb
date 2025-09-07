---
title: Aplicación. Configurador de horarios para o alumnado de matemáticas da USC
draft: false
date: "2025-09-05"
description: ""
tags: ["Novas", "MaEGA"]
authors:
  - "maega"
---

Con motivo do arranque deste curso 2025-2026 poñemos a disposición do estudantado da facultade de matemáticas unha ferramenta para axilizar o habitualmente tedioso proceso de configurar o horario lectivo ao comezo do curso académico.

Mediante un formulario, os estudantes poderán seleccionar os grupos expositivos e interactivos das asignaturas que estea a cursar, podendo ser estas de diferentes cursos. Logo de enviar o formulario recibirá un correo notificándolle que se lle acaba de compartir vía Google Drive un ficheiro PDF co seu horario personalizado.

<!-- <iframe
  src="https://forms.gle/TPJx94Dg6L1fUVgeA"
  height="620"
  width="569">
</iframe> -->

<div class="cbutton">
  <button>Configura aquí o teu horario!</button>
</div>

<style>

.cbutton {
 appearance: none;
 background-color: transparent;
 border: 0.125em solid #1A1A1A;
 border-radius: 0.9375em;
 box-sizing: border-box;
 color: #3B3B3B;
 cursor: pointer;
 display: flex; /* Cambiado a inline-flex */
 align-items: center;  /* Centrado vertical */
 justify-content: center;
 font-size: 16px;
 font-weight: 600;
 line-height: normal;
 min-height: 3.75em;
 min-width: 0;
 outline: none;
 margin: 2em 0;
 padding: .25em 1em;
 text-align: center;
 text-decoration: none;
 transition: all 300ms cubic-bezier(.23, 1, 0.32, 1);
 user-select: none;
 -webkit-user-select: none;
 touch-action: manipulation;
 will-change: transform;
}

.cbutton:is(.dark *) {
 background-color: #334155;
 border: 0.125em solid #334155;
 color: #cbd5e1;
}

.cbutton:disabled {
 pointer-events: none;
}

.cbutton:hover {
 color: #fff;
 background-color: #1A1A1A;
 box-shadow: rgba(0, 0, 0, 0.25) 0 8px 15px;
 transform: translateY(-1px);
}

.cbutton:hover:is(.dark *) {
 color: #1e293b
;
 background-color: #60a5fa;
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