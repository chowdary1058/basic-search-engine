function showSection(sectionId) {
    const sections = document.querySelectorAll(".section");
    sections.forEach(section => section.classList.remove("active"));
    document.getElementById(sectionId).classList.add("active");
}

function sendMessage() {
    const chatInput = document.getElementById("chatInput").value;
    const chatOutput = document.getElementById("chatOutput");

    if (chatInput.trim() === "") {
        chatOutput.innerHTML = "<p>Please enter a message.</p>";
        return;
    }

    // Simulate ChatGPT response (replace with actual API call)
    chatOutput.innerHTML = `<p><strong>You:</strong> ${chatInput}</p>
                            <p><strong>ChatGPT:</strong> This is a simulated response.</p>`;
}
