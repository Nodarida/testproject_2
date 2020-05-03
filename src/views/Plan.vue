
<template>
<h1>Mensa Foooood</h1>
  <select name="Wochentage" id="selectBox">

    <option>Montag</option>
    <option>Dienstag</option>
    <option>Mittwoch</option>
    <option>Donnerstag</option>
    <option>Freitag</option>

  </select>
  <br>
  <br>
  <br>

  <table>
    <tr>
      <th>Information</td>
      <th>Kategorie</td>
      <th>Kosten</td>
      <th>Tag</td>
      <th>Downvotes</td>
      <th>ID</td>
      <th>Labels</td>
      <th>Upvotes</td>
    </tr>
  </table>
</template>

<script>
export default {
  name: 'Plan',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
