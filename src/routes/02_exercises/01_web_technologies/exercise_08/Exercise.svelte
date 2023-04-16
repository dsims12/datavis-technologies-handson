<script>
    const favorite_things = ['Books', 'Succession', 'Music'];
    const student = { name: 'Diogo', fav_things: favorite_things};
</script>

<p>My name is {student.name} and  my favourite things are: </p>
<p> 
    <li>{student.fav_things[0]}</li> 
    <li>{student.fav_things[1]}</li> 
    <li>{student.fav_things[2]}</li>
</p>