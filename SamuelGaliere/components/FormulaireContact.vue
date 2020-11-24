<template>
  <div>
    <h3>
      Contact
    </h3>
    <div class="content">
      <form name="contact" action="mailto:sgaliere@emd-management.fr" method="post">
        <label class="form-label" for="name">
          Name:
        </label>
        <input class="form-field" name="name" id="name" />
        <label class="form-label" for="email">
          Email:
        </label>
        <input class="form-field" name="email" id="email" />
        <label class="form-label" for="message">
          Message:
        </label>
        <textarea class="form-field" name="message" id="message"></textarea>
        <input class="form-button" type="submit" value="Send message" />
      </form>
    </div>
  </div>
</template>

<script>
export default {
    name: "FormulaireContact",
}
</script>


<style>

</style>