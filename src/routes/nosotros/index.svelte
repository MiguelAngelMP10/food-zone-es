<script>
import { base} from '$app/paths';
export let url = base;
import { onMount } from 'svelte';


onMount(() => {
		new WOW({
			mobile: true,
			live: false,
			offset: 0,
		}).init();
	});
</script>


<div class="row">
  <main>
    <div class="position-relative overflow-hidden  bg-light ">
      <div class="col-md-12">
        <div class="row justify-content-center">
          <div class="col-8">
            <div class="row py-5">
              <h4 class=" wow animated rubberBand  text-center">FoodZone-Nosotros</h4>
              <h3 class=" wow animated rubberBand  text-center py-3">
                ¿Quiénes somos y qué hacemos?
              </h3>

              <img
                src="{url}/img/FZ1.png"
                class="igure-img img-fluid rounded wow zoomIn animated py-3" data-wow-offset="10"
                alt="..."
              />
              <p class=" wow rotateInDownRight animated" data-wow-offset="10">
                FOOD ZONE, es un software con acceso vía Web, y APP’s de iOS y
                Android para facilitar la interacción entre usuarios y los
                establecimientos de la Industria de Alimentos y Bebidas, la
                Industria de la Hospitalidad, y la Industria del
                Entretenimiento.
              </p>

              <p class=" wow rotateInDownRight animated" data-wow-offset="10">
                Permite al usuario tener una interacción cómoda, segura y
                completa para su experiencia con restaurantes y lugares de
                entretenimiento.
              </p>
              <p class=" wow rotateInDownRight animated" data-wow-offset="10">
                La plataforma permite hacer pagos con tarjeta de crédito o
                débito, así como por medio de crédito que se podrá abonar en
                efectivo al adquirir monederos electrónicos en los distintos
                puntos de venta.
              </p>
            </div>

            <div class="row py-3">
              <div class="col-sm-12 col-md-6 wow rotateInDownRight animated" data-wow-offset="10">
                <h4 class="py-5">Visión</h4>
                <p class="">
                  Posicionarnos como el software enfocado en Alimentos y Bebidas
                  más utilizado en el mercado de México y Estados Unidos.
                </p>
              </div>
              <div class="col-sm-12 col-md-6 wow rotateInUpLeft animated " data-wow-offset="10">
                <h4 class="py-5">Misión</h4>
                <p class="">
                  Brindar el mejor servicio a cada uno de nuestros clientes
                  facilitándoles el proceso de compra en establecimientos del
                  sector de Alimentos y Bebidas.
                </p>
              </div>

              <h4 class="text-center py-3">Nuestros Valores</h4>
              <div class="row">
                <div class="col wow zoomInDown animated" data-wow-offset="10">
                  <div class="card h-100">
                    <img
                      src="https://spicasoftware.es/sael/wp-content/uploads/sites/3/2020/02/aiddyIT-min.png"
                      class="card-img-top"
                      alt="..."
                      style="width: 100%;"
                    />
                    <div class="card-body">
                      <h5 class="card-title">Servicio Personalizado</h5>
                    </div>
                  </div>
                </div>
                <div class="col wow zoomInDown animated" data-wow-offset="10">
                  <div class="card h-100">
                    <img
                      src="https://www.lima-europe.eu/wp-content/uploads/2016/09/RD_wit-300x218.png"
                      class="card-img-top"
                      alt="..."
                    />
                    <div class="card-body">
                      <h5 class="card-title">Innovación</h5>
                    </div>
                  </div>
                </div>
                <div class="col wow zoomInDown animated" data-wow-offset="10">
                  <div class="card h-100">
                    <img
                      src="{url}/assets/images/calidad.png"
                      class="card-img-top"
                      alt="..."
                    />
                    <div class="card-body">
                      <h5 class="card-title">Calidad</h5>
                    </div>
                  </div>
                </div>
                <div class="col wow zoomInDown animated" data-wow-offset="10">
                  <div class="card h-100">
                    <img
                      src="https://1.bp.blogspot.com/-zz5EdQQUwDE/W2QrZnbkmVI/AAAAAAAAT0I/h6RuDL_frUQLMAeLVCeqA8VwpCJSdSIjgCEwYBhgL/s640/honestidad.png"
                      class="card-img-top"
                      alt="..."
                    />
                    <div class="card-body">
                      <h5 class="card-title">Honestidad</h5>
                    </div>
                  </div>
                </div>

                <div class="col  wow zoomInDown animated" data-wow-offset="10">
                  <div class="card h-100">
                    <img
                      src="https://freepikpsd.com/media/2019/10/responsabilidad-png-2-Transparent-Images-Free.png"
                      class="card-img-top"
                      alt="..."
                    />
                    <div class="card-body">
                      <h5 class="card-title">Responsabilidad</h5>
                    </div>
                  </div>
                </div>
              </div>

              <h4 class="text-center py-5 wow rotateInUpLeft animated" data-wow-offset="10">
                Historia de Food Zone
              </h4>
              <div class="row">
                <div class="col-sm-12 col-md-4 wow rotateInUpLeft animated" data-wow-offset="10">
                  <img
                    src="https://sites.google.com/site/portmari04/_/rsrc/1481203045409/tarea-3-cartel-la-empresa-desde-el-punto-de-vista-juridico/Existen-distintos-tipos-de-empresas.png"
                    alt=""
                  />
                </div>
                <div class="col-sm-12 col-md-8 wow rotateInUpLeft animated" data-wow-offset="10">
                  <p class=" py-5">
                    Nuestra empresa surge en 2021 de la necesidad de facilitar y
                    agilizar el servicio de alimentos y bebidas en foodcourts,
                    restaurantes y otros establecimientos. Brindamos la opción
                    de pagar con cualquier tarjeta y además, le damos a nuestros
                    clientes un beneficio por cada compra realizada desde
                    nuestra app.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</div>
