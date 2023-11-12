<script context="module" lang="ts">
    export type Techs = {
        tech: "JQuery" | "JavaScript" | "TypeScript" | "PHP" | "React" | "NextJS" | "Svelte" | "Code Igniter" | "Laravel" | "C#" | "Entity Framework" | "Asp .Net" | "MySQL" | "NoSQL" | "Node" | "Express" | "Mongo DB" | "GO" | "Ruby"
    }
    export type ExperienceProps = {
        title: string;
        subtitle: string | null;
        description: string;
        technologies: Techs['tech'][];
    }
</script>
<script lang="ts">
    export let props: ExperienceProps;
</script>
<div id="container">
    <h2>
        {props.title}
    </h2>
    {#if props.subtitle}
        <h2>
            {props.subtitle}
        </h2>
    {/if}
    <p>{props.description}</p>
    {#each props.technologies as tech }
        <span>{tech}</span>
    {/each}
</div>

<style scoped>
    #container {
        box-sizing: border-box;
        padding: 10px;
    }

    #container:hover {
        box-shadow: 1px 3px 10px rgba(204, 204, 204, 0.64);
        -webkit-box-shadow: 1px 3px 10px rgba(181, 181, 181, 0.64);
        -moz-box-shadow: 1px 3px 10px rgba(179, 179, 179, 0.64);
    }
    span {
        color: green;
    }
</style>
