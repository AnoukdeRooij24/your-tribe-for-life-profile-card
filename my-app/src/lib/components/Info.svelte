<script>
    export let member;
</script>

<div class="info">
    <div class="links">
        <a href="https://github.com/AnoukdeRooij24"> <img class="logo" src="src/lib/assets/github_logo.png" alt="{ member.github_handle }" width="50px" height="50px"> </a>
        <a href="{ member.website }"> <img class="logo" src="src/lib/assets/website_logo.png" alt="I love web" width="50px" height="50px"> </a>
    </div>
    <p> <strong>Bio:</strong> { member.bio } </p>
    <p> <strong>Birthdate:</strong> { member.birthdate } </p>
    <p> <strong>Fav emoji:</strong> { member.fav_emoji } </p>
    <p> <strong>Hobby:</strong> { member.fav_hobby } </p>
    <p> <strong>Fav animal:</strong> { member.fav_animal } </p>
</div>
