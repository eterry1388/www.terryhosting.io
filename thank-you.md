## Thank You

Thank you <span class="name"></span>for signing up!

<script>
  var email = getParameterByName('stripeEmail');
  var name = getParameterByName('stripeBillingName');
  var element = document.getElementsByClassName('name')[0];
  element.innerHTML = name + ' (' + email + ') '
</script>
