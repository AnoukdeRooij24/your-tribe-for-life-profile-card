<script>
    let { data } = $props(); 
    const member = data.member;
</script>

<article>
    <h1> { member.name }</h1>
    <img src={member.avatar} alt="{member.name} picture" width="100px" height="100px"/>

    <p> <strong>Github:</strong> { member.github_handle } </p>
    <p> <strong>Bio:</strong> { member.bio } </p>
    <p> <strong>Birthdate:</strong> { member.birthdate } </p>
    <p> <strong>Fav emoji:</strong> { member.fav_emoji } </p>
    <p> <strong>Hobby:</strong> { member.fav_hobby } </p>
    <p> <strong>Fav animal:</strong> { member.fav_animal } </p>
</article>



