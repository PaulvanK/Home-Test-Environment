<template>
  <div>
    <!-- Header -->
    <header>
      <img src="path/to/your/image.png" alt="Logo" />
    </header>

    <!-- Crisp chat -->
    <div class="chat-container">
      <!-- Crisp chat element -->
      <div id="crisp-chat"></div>

      <!-- Input field -->
      <div class="input-field">
        <input
          type="text"
          v-model="message"
          @keyup.enter="sendMessage"
          placeholder="Type your message..."
        />
        <button @click="sendMessage">Send</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: '',
    };
  },
  methods: {
    sendMessage() {
      // Logic to send the message
      // You can handle the logic to send the message to the chat service (Crisp) here
      // For example:
      if (this.message.trim() !== '') {
        // Send the message using Crisp API or your custom logic
        console.log('Sending message:', this.message);

        // Clear the input field after sending
        this.message = '';
      }
    },
  },
};
</script>

<style>
/* Styles for the layout */
header {
  display: flex;
  justify-content: flex-end;
  padding: 10px;
}

.chat-container {
  margin-top: 20px;
}

.input-field {
  display: flex;
  align-items: center;
  margin-top: 10px;
}

.input-field input {
  flex: 1;
  padding: 5px;
}

.input-field button {
  margin-left: 10px;
}
</style>
