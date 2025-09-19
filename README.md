# Raghav
html lang="en">
<div style="font-weight:800">SmartFlex X</div>
<div style="font-size:13px;color:var(--muted)">From 128GB • 8GB RAM</div>
</div>
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-ZTDSKKP9FG"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date(), { 'debug_mode':true });

  gtag('config', 'G-ZTDSKKP9FG');
</script>
<div class="price">₹39,999</div>
</div>
<div style="margin-top:auto;display:flex;gap:8px;margin-top:12px">
<button class="btn btn-primary">Buy</button>
<button class="btn" onclick="viewDetails('SmartFlex X')">Details</button>
</div>
</div>


<div class="card">
<img src="https://images.unsplash.com/photo-1542751371-adc38448a05e?q=80&w=1400&auto=format&fit=crop&ixlib=rb-4.0.3&s=efgh" alt="phone2"/>
<div style="display:flex;justify-content:space-between;align-items:center">
<div>
<div style="font-weight:800">SmartFlex Lite</div>
<div style="font-size:13px;color:var(--muted)">From 64GB • 6GB RAM</div>
</div>
<div class="price">₹19,999</div>
</div>
<div style="margin-top:auto;display:flex;gap:8px;margin-top:12px">
<button class="btn btn-primary">Buy</button>
<button class="btn" onclick="viewDetails('SmartFlex Lite')">Details</button>
</div>
</div>


<div class="card">
<img src="https://images.unsplash.com/photo-1512496015851-a90fb38ba796?q=80&w=1400&auto=format&fit=crop&ixlib=rb-4.0.3&s=ijkl" alt="phone3"/>
<div style="display:flex;justify-content:space-between;align-items:center">
<div>
<div style="font-weight:800">SmartFlex Pro</div>
<div style="font-size:13px;color:var(--muted)">From 256GB • 12GB RAM</div>
</div>
<div class="price">₹59,999</div>
</div>
<div style="margin-top:auto;display:flex;gap:8px;margin-top:12px">
<button class="btn btn-primary">Buy</button>
<button class="btn" onclick="viewDetails('SmartFlex Pro')">Details</button>
</div>
</div>
</div>
</section>


<section class="cta-strip">
<div>
<div style="font-weight:800">Limited time trade-in offer</div>
<div style="color:var(--muted);font-size:13px">Get up to ₹12,000 off when you trade in your old device.</div>
</div>
<div><button class="btn btn-primary" onclick="scrollToSection('buy')">Claim offer</button></div>
</section>


</main>


<footer>
<div>&copy; 2025 SmartFlex. All rights reserved.</div>
<div class="socials">
<a href="#">Terms</a>
<a href="#">Privacy</a>
</div>
</footer>


</div>


<script>
function scrollToSection(id){
const el = document.getElementById(id);
if(el) el.scrollIntoView({behavior:'smooth',block:'start'});
}


function subscribe(e){
e.preventDefault();
const email = document.getElementById('email').value;
if(!email) return alert('Please enter an email');
// simulate success
alert('Thanks! We\'ll notify ' + email + ' when early access opens.');
e.target.reset();
}


function viewDetails(name){
alert(name + ' — feature details coming soon!');
}
</script>
</body>
</html>
