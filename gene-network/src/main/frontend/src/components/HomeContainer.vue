<template>
  <div class="row">
    <div class="col-md-12">
      <h4>Making it work</h4>
      <ol>
        <li>Import a VCF or an EMX containing at least a Gene_Name column with HGNC symbols</li>
        <li>Using the molgenis data explorer edit this VCF entitytype and add it to diagnostics package</li>
        <li>Import HPO ontology using the molgenis upload</li>
        <li>Add an entity to Matrix metadata and add the matrix file with the GeneNetwork scores</li>
      </ol>
      <p>You should now have the VCF in the "Patients" list. Click on it and start filtering</p>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'home-container'
  }
</script>
