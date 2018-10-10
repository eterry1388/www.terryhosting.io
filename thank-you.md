## Thank You

Thank you <span class="name"></span>for signing up!

<script>
  var email = getParameterByName('stripeEmail');
  var name = getParameterByName('stripeBillingName');
  var element = document.getElementsByClassName('name')[0];
  if (email !== null && name != null) {
    element.innerHTML = name + ' (' + email + ') '
  }
</script>

<aside><a href="/" class="button">Home</a></aside>
