# VSCode-Launch.JSON
In VSCode launch.json is used for startup debug parameters.  This repo has examples for streamlit, fastapi, gradio, and other configurations that start debug optimally.


# Streamlit
"""
{
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [
        {
            "name": "Debug Streamlit",
            "type": "python",
            "request": "launch",
            "program": "C:\\Users\\aaron\\AppData\\Local\\Programs\\Python\\Python311\\Scripts\\streamlit.exe",
            "args": [
                "run",
                "app.py"
            ],
            "console": "externalTerminal",
            "justMyCode": true
        }
    ]
}
"""
