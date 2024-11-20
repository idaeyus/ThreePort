# ThreePort

**ThreePort** is a powerful tool that allows you to render 3D models generated by Language Models (LLMs) such as ChatGPT, Claude, and others.

### Key Algorithms

1. **Algo1**:  
   The core algorithm in the `index.html` file is responsible for rendering the 3D model. Algo1 connects adjacent vertices to form the model, ensuring smooth and continuous geometry.

2. **Algo2**:  
   The `algo2.txt` file offers a fallback rendering algorithm. Instead of connecting adjacent vertices, Algo2 links the vertices in the order they are listed in the JSON file. This allows for an alternative rendering method when Algo1 is not suitable.

### How to Use

1. **Launch ThreePort** in your browser.  
2. Click on **"Copy Prompt"** to generate the 3D model instructions.
3. Paste the prompt into an LLM (like ChatGPT, Claude, etc.) to generate a sample model.  
   *Note: The LLM might provide a sample model without specific instructions. Be sure to remove any comments from the JSON output, as they are not supported in ThreePort.*

4. **Copy the generated JSON content** from the LLM and paste it into ThreePort to render the 3D model.

 
