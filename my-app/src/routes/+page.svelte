<script>
    let { data } = $props(); 
    const member = data.member;
    import Info from '$lib/components/Info.svelte'
</script>

<article>
    <div class="name">
        <img src={member.avatar} alt="{member.name} picture" width="100px" height="100px"/>
        <h1> { member.name }</h1>
    </div>

    <div class="line"></div>

    <Info { member }/>

</article>



