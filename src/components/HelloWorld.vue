<template>
  <div class="hello">
  <b-card-group deck>
  <b-card
    footer=""
    footer-tag="footer"
    title="Basic Info"
    img-src=""
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 65rem;"
    class="mb-2"
  >
    <b-card-text>
------------
    </b-card-text>
    <b-list-group>
    <b-list-group-item><b>First Name:</b> Luis Felipe <br>
    <b>Last Name:</b> Viveros Bedoya <br>
    <b>Email:</b> luisfe60@hotmail.com <br>
    <b>Phone Number:</b>+573206673824 <br>
    <b>Address:</b> Calle 23a Norte # 14-24, Armenia, Quindío, Colombia 
    </b-list-group-item>
    
  </b-list-group>
  <br>
    
    <b-modal id="modal-1" title="Payment Confirmation">
    <p class="my-4">You have just booked your Vuebnb</p>
  </b-modal>
  </b-card>
<!-- end of card 1 -->
  <b-card
    footer="Generally: Some Basic Wordpress, Some Advanced Wordpress, Some headless Wordpress, Some React JS, Some Vue JS, Some PHP, Some SQL "
    footer-tag="footer"
    title="Experience"
    img-src=""
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 65rem;"
    class="mb-2"
  >
    <b-card-text>
      
    </b-card-text>
    <b-list-group>
    <b-list-group-item><strong>GSMedia (Israel)/</strong> Web developer ( February 2021 - Current Date) Web development according to mockup specifications, webmaster and technology support activities.</b-list-group-item>
    <b-list-group-item><strong>Ecore Digital Performance (Medellin)/</strong> Web developer (June 2020 - August 2020) Web development according to mockup specifications, webmaster activities.</b-list-group-item>
    <b-list-group-item><strong>RGB(Armenia)/</strong> Web Designer and web developer (2015 - Current date) Designing and programming web sites using Wordpress and CMS platforms.</b-list-group-item>
  </b-list-group>
<br>
    
    <b-modal id="modal-2" title="Payment Confirmation">
    <p class="my-4">You have just booked your Vuebnb</p>
  </b-modal>
  </b-card>
<!-- end of card 2 -->
  <b-card
    footer=""
    footer-tag="footer"
    title="Education"
    img-src=""
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 65rem;"
    class="mb-2"
  >
    <b-card-text>
    <strong>Languages/</strong> English (C1) - Instituto Colombo Americano - Native Spanish speaker.
    </b-card-text>
    <b-list-group>
    <b-list-group-item><strong>Colegio Nacional Jesus Maria Ocampo/</strong> Bachiller academico Grados 6 a 11</b-list-group-item>
    <b-list-group-item><strong>Universidad del Quindio/</strong> Licenciatura en Matematicas (5o año).</b-list-group-item>
    <b-list-group-item><strong>Sena/</strong> Programación PHP y Mysql, Programación C++, Desarrollo para Android en App inventor.</b-list-group-item>
  </b-list-group>
<br>
    <b-modal id="modal-3" title="Payment Confirmation">
    <p class="my-4">You have just booked your Vuebnb</p>
  </b-modal>
  </b-card>
<!-- end of card 3 -->
<b-card
    footer="Thanks for having a look!"
    footer-tag="footer"
    title="Some Projects"
    img-src=""
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 65rem;"
    class="mb-2"
  >
    <b-card-text>
    </b-card-text>
    <b-list-group>
    <b-list-group-item>
https://idealinsulationcompany.com/<br>
http://villarimona.com/<br>
https://bossitude.com/<br>
https://www.saberlifefoundation.org/<br>
http://yoht.org/<br>
https://mykupa.org/<br>
https://trupr.com/<br>
https://greatgameofkashrut.com/<br>
http://israelcbdshop.com/ <br>
https://lglandscaping.net/<br>
https://nature-pharm.com/<br>
http://genohr.net/<br>
http://eurodent.co/<br>
http://perrossinnombre.org/<br>
https://nkninoska.com <br>
https://btobnegocios.com/ <br>
www.produccionvisual.com/ <br>
www.montesrealtors.com <br>
www.haciendaselrancho.com<br>
https://btobnegocios.com/ <br>
https://douglasexp.com/<br>
https://kalvinoficial.com/<br>
</b-list-group-item>
    
  </b-list-group>
<br>
    <b-button href="mailto:luisfe60@hotmail.com" variant="info" v-b-modal.modal-3>Contact Me</b-button>
    <b-modal id="modal-3" title="Thanks for writing">
    <p class="my-4">I'll get back to you as soon as possible</p>
  </b-modal>
  </b-card>
<!-- end of card 4 -->
  </b-card-group>       
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  margin-left: 90px;
  padding-left: 20px;
}
.mb-2{
  padding-bottom: 30px;
}
.btn-info:hover {
    color: #fff;
    background-color: #000000;
    border-color: #000000;
}
.btn-info {
    color: #fff;
    background-color: #ff2c2c;
    border-color: #ff2c2c;
}
</style>
