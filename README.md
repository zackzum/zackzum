body {
    font-family: Arial, sans-serif;
    background: #f0f8ff;
    color: #333;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

header {
    background: linear-gradient(90deg, #4b6cb7, #182848);
    color: white;
    text-align: center;
    padding: 20px;
}

main {
    flex: 1;
    padding: 20px;
}

.dorama-list {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

.dorama-item {
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    overflow: hidden;
    width: 300px;
    text-align: center;
}

.dorama-item img {
    width: 100%;
    height: auto;
}

.dorama-item h2 {
    background: #4b6cb7;
    color: white;
    margin: 0;
    padding: 10px;
}

.dorama-item p {
    padding: 10px;
}

footer {
    background: #182848;
    color: white;
    text-align: center;
    padding: 10px;
}
