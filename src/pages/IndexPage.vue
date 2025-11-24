<template>
  <div class="flex row justify-center">
    <div class="flex column justify-center justify-start text-center" style="background-color: white;">
      <h4>e-Bike Welt Havixbeck</h4>
      <h5>Hochwertige e-Bikes und Meisterwerkstatt im Münsterland</h5>
      <text-body1>
        Wir sind spezialisiert auf hochwertige e-Bikes, bieten zu unseren Premium Marken wie Riese und Müller,
        Specialized, Van Raam und Urban Arrow aber auch günstige Einstiegsmodelle und Leasingrückläufer und wir
        garantieren darüber hinaus auch noch sehr attraktive Preis für alle Modelle mit der Bestpreis Garantie auch mit
        Leasing und 0% Finanzierung! > Mehr über uns
      </text-body1>
    </div>
    <div class="bg-primary flex column justify-center text-center">
      <h4>Meisterwerkstatt im Münsterland</h4>
      <div class="flex row text-left">
        <q-card flat square class="bg-primary flex-test">
          <q-card-section class="my-card">
            <div class="card-icon flex, justify-center centers items-center row">
              <q-icon name="warning"></q-icon>
            </div>
            <h6 class="q-mt-none">Werkstatt Service</h6>
            <text-body1>
              Neben der Neurad-Montage und Inspektionen für dein e-Bike bieten wir alle Art von Reparaturen an
              Fahrrädern
              und e-Bikes auch für v...
            </text-body1>
          </q-card-section>
        </q-card>

        <q-card flat class="bg-primary flex-test">
          <q-card-section class="my-card flex column justify-start items-start"
            style="background: radial-gradient(circle, #35a2ff 0%, #014a88 100%)">
            <div class="card-icon flex, justify-center centers items-center row">
              <q-icon name="warning"></q-icon>
            </div>
            <h6 class="q-my-md">Werkstatt Service</h6>
            <text-body1>
              Neben der Neurad-Montage und Inspektionen für dein e-Bike bieten wir alle Art von Reparaturen an
              Fahrrädern
              und e-Bikes auch für v...
            </text-body1>
          </q-card-section>
        </q-card>

        <q-card flat class="bg-primary flex-test">
          <q-card-section class="my-card" style="background: radial-gradient(circle, #35a2ff 0%, #014a88 100%)">
            <div class="card-icon flex, justify-center centers items-center row">
              <q-icon name="warning"></q-icon>
            </div>
            <h6>Werkstatt Service</h6>
            <text-body1>
              Neben der Neurad-Montage und Inspektionen für dein e-Bike bieten wir alle Art von Reparaturen an
              Fahrrädern
              und e-Bikes auch für v...
            </text-body1>
          </q-card-section>
        </q-card>
      </div>
    </div>
  </div>
</template>

<script setup>
//
</script>

<style lang="scss">
.my-card {
  padding: 0px 40px 30px 40px;
  margin-left: 30px;
  margin-bottom: 30px;
  background-color: white;
}

.flex-test {
  flex: 1 1 300px;
  min-width: 150px;
}

.card-icon {
  width: 60px;
  height: 60px;
  background-color: $primary;

}
</style>