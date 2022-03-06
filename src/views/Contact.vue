<template>
  <b-container>
    <div class="mb-3">
      <label for="emailInput" class="form-label">Email address</label>
      <input type="email" class="form-control" id="emailInput" placeholder="name@example.com">
    </div>
    <div class="mb-3">
      <label for="subjectInput" class="form-label">Subject</label>
      <input type="email" class="form-control" id="subjectInput" placeholder="Subject">
    </div>
    <div class="mb-3">
      <label for="messageInput" class="form-label">Your Messages</label>
      <textarea class="form-control" id="messageInput" rows="3"></textarea>
    </div>
    <div class="col-auto">
      <button type="submit" class="btn btn-priv">Send</button>
    </div>
  </b-container>
</template>
