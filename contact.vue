<template>
    <div class="contact">
        <div class="container contact-container">
        <div class="row">
            <!-- Contact Information Section -->
            <div class="col-md-5 contact-header">
                <h1>{{ msg }}</h1>
                <p>Email: <a href="mailto:NoToTuitionFeeIncrease@example.com">NoToTuitionFeeIncrease@example.com</a></p>
                <p>Address: #2 Holy Angel Street, Angeles City, Pampanga 2009</p>
            </div>
            <!-- Contact Form Section -->
            <div class="col-md-7 contact-form">
                <p>Do you have any queries, or something to share with us? Feel free to contact us!</p>
                <form>
                    <div class="row">
                        <!-- First and Last Name -->
                        <div class="col-md-6">
                            <input type="text" class="form-control" placeholder="First name (required)" required>
                        </div>
                        <div class="col-md-6">
                            <input type="text" class="form-control" placeholder="Last name (required)" required>
                        </div>
                    </div>
                    <!-- Email -->
                    <div class="row">
                        <div class="col-md-12">
                            <input type="email" class="form-control" placeholder="Email (required)" required>
                        </div>
                    </div>
                    <!-- Message -->
                    <div class="row">
                        <div class="col-md-12">
                            <textarea class="form-control" rows="6" placeholder="Message"></textarea>
                        </div>
                    </div>
                    <!-- Submit Button -->
                    <button type="submit" class="btn btn-dark mt-3">Submit</button>
                </form>
            </div>
        </div>
    </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'contact',
    data() {
      return {
        msg: 'Contact '
      }
    }
  }
  </script>
  <style scoped>

  </style>