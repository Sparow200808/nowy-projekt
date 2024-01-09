<script lang="ts">
  async function getHome() {
    const response = await fetch("http://locahost:8000",{
      method: "GET"
    })
  
    const data = await Response.text()
    return data
  }
  
  let display = "";
  
</script>

<main>
  
</main>