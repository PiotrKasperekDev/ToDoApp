<template>
  <section class="hero">
    <div class="container">
      <div class="text-container">
        <h1>Manage Your Time!</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi
          voluptatum dolores, autem minima necessitatibus vero dolore. Rerum nam
          neque, obcaecati quos, deleniti impedit doloremque exercitationem
          repudiandae nulla, officia dolor vero? Voluptate dolorum optio ab
          officiis. Consequuntur minus nihil veniam animi eum vero alias commodi
          iure maiores, repellat ex sapiente voluptatibus? Earum voluptate
          exercitationem rem nulla quisquam. Et alias omnis rem. Earum
          laudantium expedita dolore soluta, quos numquam magni repudiandae at
          ex quas, itaque nesciunt reprehenderit velit esse magnam eaque nobis
        </p>
        <router-link :to="{ name: 'AddProject' }">
          <button class="hero-button">Create New Task</button>
        </router-link>
      </div>
      <div class="image-container">
        <img src="../assets/logo.png" alt="" />
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.hero {
  margin-top: 100px;
}
.hero .container {
  max-width: 1000px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.hero .container .text-container {
  max-width: 650px;
}

.hero .container .text-container .hero-button {
  padding: 15px;
  border: none;
  border-radius: 5px;
  color: #fff;
  background: #07b969;
  cursor: pointer;
}
</style>
