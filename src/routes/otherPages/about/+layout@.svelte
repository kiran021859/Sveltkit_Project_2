<script>
    import Title from '$lib/title.svelte'
    import '../../../global css/style.css'
    </script>
    
    <header>
    <Title title="this is the layout"/>
    <div class="links">
        <a href="/">Home</a>
        <a href="/guids">Guids</a>
    </div>
    </header>
    
    <main>
    <slot></slot>
    </main>
    
    <footer>
        <p>Copyright 2024 Kiran Isaacs Svelt test web site</p>
    </footer>
    
    <style>
        header {
            display: flex;
            justify-content: space-between;
            background-color: rgba(0,0,0,0.1);
        }
        main {
            max-width: 960px;
            margin: 20px auto;
        }
        footer {
            text-align: center;
        }
        .links {
            width: 10%;
            display: flex;
            align-items: center;
            justify-content: space-around;
            margin-right: 50px;
            
        }
    </style>