<!DOCTYPE html>
<html>

<head>
    <title>PyAutoGUI Auto Typer</title>
</head>

<body>

    <h1>PyAutoGUI Auto Typer</h1>

    <p>This Python script is designed to automate text input using the PyAutoGUI library. It can be useful for scenarios
        where repetitive typing is required, such as testing or data entry. The script simulates keyboard input to
        repeatedly type a specified message and press "enter" at regular intervals.</p>

    <h2>Prerequisites</h2>

    <p>Before running the script, make sure you have Python installed on your system. You can install the required
        library using the following command:</p>

    <pre><code>pip install pyautogui</code></pre>

    <h2>Usage</h2>

    <ol>
        <li><strong>Clone the repository:</strong>
            <pre><code>git clone https://github.com/your-username/auto-typer.git
cd auto-typer</code></pre>
        </li>

        <li><strong>Open the script:</strong>
            <p>Open the script (<code>auto_typer.py</code>) in a text editor and replace the placeholder message with
                the text you want to be typed:</p>
            <pre><code>pyautogui.typewrite("Type your Message here")</code></pre>
        </li>

        <li><strong>Adjust the sleep duration:</strong>
            <p>Modify the sleep duration if needed to control the time delay between each typing action:</p>
            <pre><code>time.sleep(3)</code></pre>
        </li>

        <li><strong>Run the script:</strong>
            <p>Execute the script using the following command:</p>
            <pre><code>python auto_typer.py</code></pre>
        </li>
    </ol>

    <h2>Important Notes</h2>

    <ul>
        <li>This script runs indefinitely. To stop it, you may need to terminate the script manually.</li>
        <li>Ensure the focus is on the application where you want the text to be typed.</li>
    </ul>

    <h2>Contribution</h2>

    <p>If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull
        request. Your contributions are welcome!</p>

    <p>Happy typing!</p>

</body>

</html>
