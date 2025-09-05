# ChatGPT Promt Text Chunker

**ChatGPT Promt Text Chunker** is a lightweight offline web tool that allows you to split long text into smaller chunks. This is useful for sending text to ChatGPT without exceeding its input limits while keeping the chunks organized with labels like `[Part 1/N]`.

---

## Features

- Split long text into safe-sized chunks (default: 11,800 characters).  
- Automatically label chunks as `[Part i/N]`.  
- Copy chunks with a single click.  
- Smooth fade and slide animation for copied chunks.  
- Customizable max characters per chunk.  
- Beautiful gradient background with optional image overlay in text areas.  
- Fully offline – works in any browser without server or internet.

---

## Usage

1. Open `index.html` in your browser.  
2. Paste your long text into the main text area.  
3. Adjust the **Max characters per chunk** if needed.  
4. Click **Split** to generate chunks.  
5. Click **Copy** on each chunk to copy it to your clipboard. The chunk will fade away to indicate it has been copied.

---

## Project Structure

chatgpt-promt-text-chunker/
│
├─ chatgpt-promt-text-chunker.html # Main tool file
├─ bg.jpg # Optional background image
└─ README.md # Project description (this file)

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.
