<style>
    
    body {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            background-color: pink;
        }

 .animation-container {
            text-align: ;
            color: black;
            font-size: 24px;
        }

        .loader {
            border: 4px solid rgba(255, 255, 255, 0.3);
            border-top: 4px solid #fff;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            animation: spin 2s linear infinite;
            color: black;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        p{
            color: #222;
        }
</style>

    <div class="container" style="background-image: url('pngtree-cyber-security-data-dark-blue-light-effect-abstract-background-image_771333.jpg')>
<p>Your Login successfully....please Wait a few Second </p><ul></ul>
<p id="adviceText"></p>
    <div class="animation-container">
        <div class="loader"></div>
      
   
<script>
    // Function to redirect to the second page after 10 seconds
    function redirectToSecondPage() {
            window.location.href = "second_page.html";
        }

        // Add event listeners to each button (like in your original code)

        // Call redirectToSecondPage after a 20-second delay
        setTimeout(redirectToSecondPage, 20000); // 20000 milliseconds = 20 seconds
</script>
