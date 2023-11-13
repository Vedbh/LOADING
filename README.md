

<style>
    /* Assuming the repository name is in an element with the class "LOADING" */
.repository-name {
    outline: none; /* This removes the blue outline */
    /* Add other styling as needed */
}
    body {
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100vh;
        margin: 0;
        background: url('loading.jpg') center/cover no-repeat; /* 'loading.jpg' with the actual path to your image */
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
            color: white;
        }
</style>

   <p>Your Login successfully....please Wait a few Second </p><ul></ul>

<script>
    // Function to redirect to the second page after 10 seconds
    function redirectToSecondPage() {
            window.location.href = "https://vedbh.github.io/WELCOME-THIS-PAGE/";
        }

        // Add event listeners to each button (like in your original code)

        // Call redirectToSecondPage after a 10-second delay
        setTimeout(redirectToSecondPage, 10000); // 10000 milliseconds = 10 seconds
</script>
