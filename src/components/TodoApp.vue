<template>
  <div class="container">
    <h1 class="text-center mt-5">
      TesTiNg
    </h1>
    
    <!-- Input component -->
    <div class="d-flex">
      <input type="text" placeholder="Enter Task" class="form-control">
      <button class="btn btn-warning rounded-0">Submit</button>
    </div>

    <!-- Task Table -->
    <div>
      <table class="table table-bordered mt-5">
        <thead>
          <tr>
            <th scope="col">
              Task
            </th>
            <th scope="col">
              Status
            </th>
            <th scope="col">
              #
            </th>
            <th scope="col">
              #
            </th>
          </tr>
        </thead>
      </table>
    </div>
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

</style>
