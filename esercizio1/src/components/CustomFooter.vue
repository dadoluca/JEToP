<template>
    <mdb-footer color="blue" class="font-small pt-4 mt-4 fixed-bottom custom-footer">
      <mdb-container class="text-left">
        <mdb-row>
            <div class="footer-icon">
                <img src="../images/socials.png" style="width: 170px;">
            </div>
        </mdb-row>
        <!--<mdb-row>
            <div class="footer-icon">
                <img src="../images/foot.png"/>
            </div>
        </mdb-row>-->
      </mdb-container>
      <div class="footer-copyright text-center py-3">
        <mdb-container fluid style="  color: white;
  font-size: 1500;">
          &copy; 2023 Class Technologies Inc.
        </mdb-container>
      </div>
    </mdb-footer>
  </template>
  
  <style>
  .custom-footer {
    background-color: rgba(73, 56, 46, 0.65); /* Colore di sfondo con opacità */
    height: min-content;
  }
  </style>

  <script>
  export default {
    name: 'CustomFooter', // Sostituisci 'CustomFooter' con il nome che preferisci
  }
  </script>
  