<script>
    import { posts } from './postdata.js';
    console.log("Loaded")
</script>



<h1>Sileo's blog</h1>
<p>Here's a list of posts I have made. I also revamped this blog to make it snappier and easier to use.</p>

<ul>

    {#each posts as post}
    <li>
        <a href="/blog/{post.slug}">{post.title}</a>
    </li>  
    {/each}
    
</ul>