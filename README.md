<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <h1>Exemplos de Grid Layout</h1>
    <div class="grid-template">
        <h2>1. Exemplo com grid-template</h2>
        <div class="grid">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
        </div>
    </div>

    <div class="grid-column-row-gap">
        <h2>2. Exemplo com column-gap, row-gap, grid-column-gap e grid-row-gap</h2>
        <div class="grid">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
        </div>
    </div>

    <div class="justify-items">
        <h2>3. Exemplo com justify-items</h2>
        <div class="grid">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
        </div>
    </div>

    <div class="align-items">
        <h2>4. Exemplo com align-items</h2>
        <div class="grid">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class "item">3</div>
            <div class="item">4</div>
        </div>
    </div>

    <div class="justify-content">
        <h2>5. Exemplo com justify-content</h2>
        <div class="grid">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
        </div>
    </div>

    <div class="align-content">
        <h2>6. Exemplo com align-content</h2>
        <div class="grid">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
        </div>
    </div>

    <div class="grid-auto">
        <h2>7. Exemplo com grid-auto</h2>
        <div class="grid">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
        </div>
    </div>
</body>
</html>
.grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, 100px);
    gap: 10px;
    margin: 10px;
    border: 2px solid #333;
}

.item {
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #3498db;
    color: #fff;
    font-size: 24px;
}

.grid-column-row-gap {
    grid-column-gap: 20px;
    grid-row-gap: 30px;
}

.justify-items {
    justify-items: center;
}

.align-items {
    align-items: center;
}

.justify-content {
    justify-content: center;
}

.align-content {
    align-content: center;
}

.grid-auto {
    grid-template-columns: 100px 100px;
    grid-auto-rows: 100px;
}
