body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: flex-start; /* Aligns the form to the left */
    background-color: #f4f4f4;
}

.sign-in-form {
    padding: 20px;
    margin-left: 20px; /* Keeps some distance from the very left edge */
    background-color: #fff;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
}

h2 {
    text-align: left;
}

form {
    display: flex;
    flex-direction: column;
}

label, input {
    margin-bottom: 10px;
}

button {
    padding: 10px;
    background-color: #28a745;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #218838;
}
