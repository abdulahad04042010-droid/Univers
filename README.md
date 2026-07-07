<style>
    body {
        margin: 0;
        overflow: hidden;
        background-color: #010103;
        font-family: 'Inter', -apple-system, sans-serif;
        color: #fff;
    }
    canvas { display: block; }
    #overlay {
        position: absolute;
        inset: 0;
        pointer-events: none;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        padding: 40px;
        background: radial-gradient(circle at center, transparent 30%, rgba(0,0,0,0.5) 100%);
        z-index: 10;
    }
    .header { text-align: center; }
    .title {
        font-size: 1.2rem;
        letter-spacing: 0.8em;
        text-transform: uppercase;
        color: #fff;
        margin-bottom: 12px;
        font-weight: 300;
        opacity: 0.9;
    }
