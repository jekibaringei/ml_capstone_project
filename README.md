# Waste Classification Into Craft

### This application serves to diminish recyclable waste by transforming it into valuable resources, recognizing that all individuals inevitably generate waste, a portion of which can be recycled while some cannot.

# Setup

## Create Python Environment

### You can use anything you want to use, like Python env or Anaconda

### 1. Python Env

### 2. Anaconda

# Install The Packages

<div>
       <pre><code id="install-code">pip install -r requirements.txt</code></pre>
       <button onclick="copyToClipboard('#install-code')">Copy</button>
</div>
<script>
function copyToClipboard(element) {
    var copyText = document.querySelector(element).textContent;
    var textarea = document.createElement('textarea');
    textarea.textContent = copyText;
    document.body.appendChild(textarea);
    textarea.select();
    document.execCommand('copy');
    document.body.removeChild(textarea);
    alert('Copied to clipboard');
}
</script>
