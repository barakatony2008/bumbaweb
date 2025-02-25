<template>
<form>
<label for="id">id</label>
<input type="text"><br>
<label for="Names">Names</label>
<input type="text"><br>
<label for="sex">sex</label>
<select>
<option value="male"></option>
<option value="female"></option>
</select><br>
<label for="adress">adress</label>
<input type="text"><br>
<label for="email">email</label>
<input type="text"><br>
<input type="button" value="submit">
</form>
</template>
<script>
export default{
    name:'studentregistration_component'
}
</script>
<style>
#form {
    color:blue;
    background-color:green;
    text-align:center;
}
</style>