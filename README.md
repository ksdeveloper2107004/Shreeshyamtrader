<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Shree Shyam Traders — Packaged Drinking Water Distributor</title>
  <meta name="description" content="Shree Shyam Traders - Wholesale & retail distributor of packaged drinking water. Trusted brands, pure water, fast delivery. Get a quote or place quick orders via WhatsApp: +91 9122422802." />
  <meta name="keywords" content="bottled water, wholesale water distributor, packaged drinking water, Shree Shyam Traders, drinking water bottles" />
  <meta name="author" content="Shree Shyam Traders" />
  <link rel="canonical" href="https://example.com/" />

  <!-- JSON-LD Organization + sample product structured data -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Organization",
    "name": "Shree Shyam Traders",
    "url": "https://example.com/",
    "logo": "https://via.placeholder.com/300x80.png?text=Shree+Shyam+Traders",
    "sameAs": ["https://www.facebook.com/share/1HMeZbvTKF/"]
  }
  </script>

  <style>
    :root{
      --blue-500: #0ea5e9;
      --blue-600: #0284c7;
      --bg: #f8fbff;
      --card: #ffffff;
      --muted: #6b7280;
      --green: #10b981;
      --shadow: 0 8px 24px rgba(2,132,199,0.08);
      --glass: rgba(255,255,255,0.6);
      --accent-gradient: linear-gradient(135deg, rgba(14,165,233,0.12), rgba(2,132,199,0.06));
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:var(--bg);color:#0b1220;line-height:1.45}
    a{color:var(--blue-600);text-decoration:none}

    /* Header */
    .topbar{background:linear-gradient(90deg,#eef9ff, #f4fbff);padding:6px 16px;font-size:14px;color:var(--muted);display:flex;justify-content:space-between;align-items:center}
    .container{max-width:1150px;margin:0 auto;padding:20px}
    header{display:flex;align-items:center;justify-content:space-between;padding:12px 0}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:52px;height:52px;border-radius:10px;background:var(--accent-gradient);display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--blue-600)}
    .brand h1{font-size:20px;margin:0}
    nav{display:flex;gap:14px;align-items:center}
    .nav-link{padding:8px 12px;border-radius:8px;font-weight:600}
    .nav-link:hover{background:rgba(14,165,233,0.06)}

    /* Hero */
    .hero{background:var(--card);border-radius:14px;padding:28px;display:grid;grid-template-columns:1fr 420px;gap:24px;align-items:center;box-shadow:var(--shadow)}
    .hero h2{margin:0 0 10px;font-size:28px}
    .hero p{color:var(--muted);margin:0 0 16px}
    .hero .cta{display:flex;gap:12px}
    .btn{background:var(--blue-600);color:white;padding:12px 18px;border-radius:10px;border:none;cursor:pointer;font-weight:700}
    .btn.secondary{background:transparent;color:var(--blue-600);border:1px solid rgba(2,132,199,0.12)}

    /* Products grid */
    .categories{display:flex;gap:12px;margin-top:18px;flex-wrap:wrap}
    .category-tab{padding:8px 12px;border-radius:999px;background:transparent;border:1px solid rgba(2,132,199,0.06);cursor:pointer}
    .category-tab.active{background:var(--blue-600);color:white}

    .catalog{margin-top:18px;display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
    .card{background:var(--card);border-radius:12px;padding:12px;box-shadow:0 6px 18px rgba(2,132,199,0.04);display:flex;flex-direction:column}
    .card img{width:100%;height:160px;object-fit:contain;border-radius:10px;background:#f2f9ff;padding:8px}
    .product-title{font-weight:700;margin:10px 0 6px}
    .product-desc{color:var(--muted);font-size:14px;margin:0 0 8px}
    .product-meta{display:flex;justify-content:space-between;align-items:center}
    .price{font-weight:800}
    .qty{width:72px;padding:6px;border-radius:8px;border:1px solid #e6eef7}
    .actions{display:flex;gap:8px;margin-top:10px}
    .granular{display:flex;gap:8px;align-items:center}

    /* Cart modal */
    .cart-btn{position:relative}
    .cart-count{position:absolute;top:-8px;right:-8px;background:var(--green);color:white;border-radius:999px;padding:4px 7px;font-size:12px}
    .modal{position:fixed;right:18px;bottom:90px;background:var(--card);width:360px;max-width:94%;border-radius:12px;box-shadow:0 18px 40px rgba(2,132,199,0.12);overflow:hidden;display:none;flex-direction:column}
    .modal.open{display:flex}
    .modal .head{padding:12px 16px;border-bottom:1px solid #f1f6fb;display:flex;justify-content:space-between;align-items:center}
    .modal .body{padding:12px 16px;max-height:320px;overflow:auto}
    .modal .foot{padding:12px 16px;border-top:1px solid #f1f6fb;display:flex;justify-content:space-between;align-items:center}

    /* Footer */
    footer{margin-top:28px;padding:24px 0;border-top:1px solid #e8f3fb;background:transparent}
    .footer-grid{display:flex;gap:18px;flex-wrap:wrap}

    /* Quick order sticky */
    .quick-order{position:fixed;right:18px;bottom:18px;background:linear-gradient(90deg,var(--blue-600),var(--blue-500));color:white;padding:14px 16px;border-radius:12px;display:flex;gap:10px;align-items:center;box-shadow:0 12px 30px rgba(2,132,199,0.18);z-index:60}
    .quick-order a{color:white;font-weight:700}

    /* Responsive */
    @media (max-width:1000px){
      .hero{grid-template-columns:1fr;}
      .catalog{grid-template-columns:repeat(2,1fr)}
    }
    @media (max-width:640px){
      nav{display:none}
      .catalog{grid-template-columns:1fr}
      header{padding-bottom:8px}
      .container{padding:12px}
      .hero{padding:18px}
      .quick-order{right:12px;bottom:12px}
    }

    /* subtle animations */
    .fade-in{animation:fadeIn .6s ease both}
    @keyframes fadeIn{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}
  </style>
</head>
<body>
  <div class="topbar container">
    <div>Serving purity & trust — Fast delivery across the service area</div>
    <div>WhatsApp Orders: <a href="https://wa.me/919122422802?text=Hi%20Shree%20Shyam%20Traders%2C%20I%27d%20like%20to%20place%20an%20order" target="_blank">+91 91224 22802</a></div>
  </div>

  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">SS</div>
        <div>
          <h1>Shree Shyam Traders</h1>
          <div style="font-size:13px;color:var(--muted)">Wholesale & Retail • Packaged Drinking Water</div>
        </div>
      </div>

      <nav>
        <a class="nav-link" href="#home">Home</a>
        <a class="nav-link" href="#products">Products</a>
        <a class="nav-link" href="#about">About</a>
        <a class="nav-link" href="#contact">Contact</a>
        <a class="nav-link" href="https://www.facebook.com/share/1HMeZbvTKF/" target="_blank">Facebook</a>
        <button id="openCart" class="btn cart-btn">Cart <span id="cartCount" class="cart-count" style="display:none">0</span></button>
      </nav>
    </header>

    <!-- HERO -->
    <section class="hero fade-in" id="home">
      <div>
        <h2>Pure water. Trusted brands. Fast delivery.</h2>
        <p>Shree Shyam Traders supplies packaged drinking water in bulk and single-unit orders. Choose from trusted brands — Clear, Biofina, Mahi Aqua and more. We serve both retail and wholesale customers with quick delivery.</p>

        <div class="cta">
          <button class="btn" onclick="document.getElementById('products').scrollIntoView({behavior:'smooth'})">Shop Products</button>
          <button class="btn secondary" onclick="openQuickOrder()">Quick Order / Get Quote</button>
        </div>

        <div style="margin-top:18px;color:var(--muted);font-size:13px">Call / WhatsApp to place orders: <a href="tel:09122422802">091224 22802</a></div>
        <div style="margin-top:10px;color:var(--muted);font-size:13px">Email: <a href="mailto:orders@shreeshyamtraders.example">orders@shreeshyamtraders.example</a></div>
      </div>

      <div style="padding:8px;display:flex;flex-direction:column;gap:12px">
        <img src="https://via.placeholder.com/420x260.png?text=Pure+Water" alt="Pure water - Shree Shyam Traders" style="border-radius:12px;object-fit:cover;box-shadow:var(--shadow)">
        <div style="background:var(--glass);padding:12px;border-radius:10px"> 
          <strong>Why choose us?</strong>
          <ul style="margin:6px 0 0;color:var(--muted);font-size:14px;padding-left:18px">
            <li>Trusted & tested brands</li>
            <li>Competitive wholesale pricing</li>
            <li>Reliable, fast delivery</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Categories and Products -->
    <section id="products" style="margin-top:18px">
      <div style="display:flex;justify-content:space-between;align-items:center">
        <h3 style="margin:0">Products</h3>
        <div style="color:var(--muted);font-size:14px">Filter by size</div>
      </div>

      <div class="categories">
        <button class="category-tab active" data-cat="200">200ml Bottles</button>
        <button class="category-tab" data-cat="500">500ml Bottles</button>
        <button class="category-tab" data-cat="1000">1 Litre Bottles</button>
        <button class="category-tab" data-cat="2000">2 Litre Bottles</button>
      </div>

      <!-- catalog container -->
      <div id="catalog" class="catalog">
        <!-- sample product card -> repeated by JS on load -->
      </div>
    </section>

    <!-- About -->
    <section id="about" style="margin-top:28px">
      <div style="display:flex;gap:18px;align-items:center">
        <div style="flex:1">
          <h3>About Shree Shyam Traders</h3>
          <p style="color:var(--muted)">Shree Shyam Traders is a trusted wholesale and retail distributor of packaged drinking water. Our mission is to provide pure, safe drinking water across our service area with a focus on reliability and customer satisfaction. We partner with well-known brands and ensure fast delivery for both single and bulk orders.</p>
          <p style="color:var(--muted)"><strong>Service Areas:</strong> Local city & nearby districts. For specific delivery zones, contact our sales team.</p>
        </div>
        <div style="width:280px;border-radius:12px;overflow:hidden;box-shadow:var(--shadow)">
          <img src="https://via.placeholder.com/420x220.png?text=Warehouse+%26+Delivery" alt="Warehouse and delivery" style="width:100%;display:block">
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" style="margin-top:28px">
      <h3>Contact Us</h3>
      <div style="display:grid;grid-template-columns:1fr 360px;gap:20px;margin-top:12px">
        <div>
          <form id="contactForm" class="card" onsubmit="submitContact(event)">
            <label style="font-weight:700">Name</label>
            <input required id="c_name" type="text" style="width:100%;padding:10px;margin:8px 0;border-radius:8px;border:1px solid #e6eef7">
            <label style="font-weight:700">Phone</label>
            <input required id="c_phone" type="tel" style="width:100%;padding:10px;margin:8px 0;border-radius:8px;border:1px solid #e6eef7">
            <label style="font-weight:700">Email</label>
            <input id="c_email" type="email" style="width:100%;padding:10px;margin:8px 0;border-radius:8px;border:1px solid #e6eef7">
            <label style="font-weight:700">Message</label>
            <textarea id="c_msg" rows="4" style="width:100%;padding:10px;margin:8px 0;border-radius:8px;border:1px solid #e6eef7"></textarea>
            <div style="display:flex;gap:10px;align-items:center;margin-top:8px">
              <button class="btn" type="submit">Send Message</button>
              <a class="btn secondary" href="https://wa.me/919122422802?text=Hello%20Shree%20Shyam%20Traders%2C%20I%20have%20a%20query" target="_blank">WhatsApp</a>
            </div>
          </form>
        </div>

        <div>
          <div class="card" style="padding:12px">
            <strong>Location</strong>
            <div style="color:var(--muted);font-size:14px;margin-top:8px">Find us on the map or visit our store during working hours.</div>
            <div style="margin-top:12px;height:220px;overflow:hidden;border-radius:10px;border:1px solid #eef7ff">
              <iframe title="Shree Shyam Traders location" src="https://www.google.com/maps?q=Shree+Shyam+Traders&output=embed" style="width:100%;height:100%;border:0"></iframe>
            </div>
            <div style="margin-top:8px;font-size:14px;color:var(--muted)">
              <div><strong>Phone:</strong> <a href="tel:09122422802">091224 22802</a></div>
              <div><strong>Email:</strong> <a href="mailto:orders@shreeshyamtraders.example">orders@shreeshyamtraders.example</a></div>
              <div style="margin-top:6px"><a href="https://www.facebook.com/share/1HMeZbvTKF/" target="_blank">Facebook Page</a></div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <footer>
      <div class="footer-grid">
        <div style="flex:1">
          <strong>Shree Shyam Traders</strong>
          <div style="color:var(--muted);font-size:14px;margin-top:8px">Trusted distributor of packaged drinking water. Fast delivery & competitive bulk pricing.</div>
        </div>
        <div style="min-width:220px">
          <strong>Quick Links</strong>
          <div style="display:flex;flex-direction:column;margin-top:8px">
            <a href="#products">Products</a>
            <a href="#contact">Contact</a>
            <a href="#about">About</a>
          </div>
        </div>
        <div style="min-width:220px">
          <strong>Contact</strong>
          <div style="color:var(--muted);font-size:14px;margin-top:8px">Phone: <a href="tel:09122422802">091224 22802</a></div>
          <div style="color:var(--muted);font-size:14px;margin-top:6px">WhatsApp: <a href="https://wa.me/919122422802?text=I%20want%20to%20order" target="_blank">+91 91224 22802</a></div>
        </div>
      </div>
    </footer>
  </div>

  <!-- Quick Order Floating Button -->
  <div class="quick-order" role="button" onclick="openQuickOrder()">
    <div style="font-weight:800">Quick Order</div>
    <a href="https://wa.me/919122422802?text=Hi%20Shree%20Shyam%20Traders%2C%20I%20want%20a%20quote" target="_blank">WhatsApp</a>
  </div>

  <!-- Cart Modal -->
  <div id="cartModal" class="modal" aria-hidden="true">
    <div class="head">
      <div style="font-weight:800">Your Order</div>
      <div><button onclick="toggleCart()" class="btn secondary">Close</button></div>
    </div>
    <div class="body" id="cartBody">
      <div style="color:var(--muted)">Your cart is empty.</div>
    </div>
    <div class="foot">
      <div style="font-weight:800">Total: <span id="cartTotal">₹0</span></div>
      <div style="display:flex;gap:8px">
        <button class="btn" onclick="checkout()">Checkout</button>
        <button class="btn secondary" onclick="clearCart()">Clear</button>
      </div>
    </div>
  </div>

  <!-- Quick Order Modal (simple prompt) -->
  <div id="quickOrderModal" style="display:none;position:fixed;left:0;top:0;right:0;bottom:0;background:rgba(2,6,23,0.45);align-items:center;justify-content:center;z-index:80">
    <div style="background:var(--card);padding:18px;border-radius:12px;max-width:520px;width:94%">
      <h3 style="margin-top:0">Quick Order / Get Quote</h3>
      <form id="quickForm" onsubmit="submitQuickOrder(event)">
        <div style="display:flex;gap:8px;flex-wrap:wrap">
          <input id="q_name" placeholder="Name" required style="flex:1;padding:10px;border-radius:8px;border:1px solid #e6eef7">
          <input id="q_phone" placeholder="Phone (required)" required style="flex:1;padding:10px;border-radius:8px;border:1px solid #e6eef7">
        </div>
        <div style="margin-top:8px">
          <label style="font-weight:700">Order details (brand, size, qty)</label>
          <textarea id="q_details" rows="4" placeholder="E.g. 500ml Mahi Aqua - 200 pieces" style="width:100%;padding:10px;border-radius:8px;border:1px solid #e6eef7"></textarea>
        </div>
        <div style="display:flex;gap:8px;justify-content:flex-end;margin-top:10px">
          <button class="btn secondary" type="button" onclick="closeQuickOrder()">Cancel</button>
          <button class="btn" type="submit">Send via WhatsApp / Email</button>
        </div>
      </form>
    </div>
  </div>

  <script>
    // Sample product data
    const PRODUCTS = [
      // 200ml
      {id: '200-1', size:200, brand:'Clear', title:'Clear 200ml', desc:'Small sip-friendly bottle', price:18, image:'https://via.placeholder.com/400x300.png?text=Clear+200ml'},
      {id: '200-2', size:200, brand:'Biofina', title:'Biofina 200ml', desc:'Trusted purity', price:16, image:'https://via.placeholder.com/400x300.png?text=Biofina+200ml'},
      // 500ml
      {id: '500-1', size:500, brand:'Mahi Aqua', title:'Mahi Aqua 500ml', desc:'Portable drinking water', price:22, image:'https://via.placeholder.com/400x300.png?text=Mahi+Aqua+500ml'},
      {id: '500-2', size:500, brand:'Clear', title:'Clear 500ml', desc:'Popular everyday bottle', price:20, image:'https://via.placeholder.com/400x300.png?text=Clear+500ml'},
      // 1L
      {id: '1000-1', size:1000, brand:'Biofina', title:'Biofina 1L', desc:'Large everyday bottle', price:35, image:'https://via.placeholder.com/400x300.png?text=Biofina+1L'},
      {id: '1000-2', size:1000, brand:'Mahi Aqua', title:'Mahi Aqua 1L', desc:'Value pack bottle', price:32, image:'https://via.placeholder.com/400x300.png?text=Mahi+Aqua+1L'},
      // 2L
      {id: '2000-1', size:2000, brand:'Clear', title:'Clear 2L', desc:'For home and office', price:60, image:'https://via.placeholder.com/400x300.png?text=Clear+2L'},
      {id: '2000-2', size:2000, brand:'Mahi Aqua', title:'Mahi Aqua 2L', desc:'Bulk drinking bottle', price:58, image:'https://via.placeholder.com/400x300.png?text=Mahi+Aqua+2L'}
    ];

    // Cart state
    let cart = {};

    function $(sel){return document.querySelector(sel)}
    function $all(sel){return Array.from(document.querySelectorAll(sel))}

    function renderCatalog(filterSize){
      const catalog = $('#catalog');
      catalog.innerHTML = '';
      const filtered = PRODUCTS.filter(p => !filterSize || p.size==filterSize);
      filtered.forEach(p=>{
        const card = document.createElement('div');card.className='card fade-in';
        card.innerHTML = `
          <img src="${p.image}" alt="${p.title}" />
          <div class="product-title">${p.title}</div>
          <div class="product-desc">${p.desc} • <strong>${p.brand}</strong></div>
          <div class="product-meta">
            <div class="price">₹${p.price}</div>
            <div class="granular">
              <input type="number" min="1" value="1" data-id="${p.id}" class="qty" />
            </div>
          </div>
          <div class="actions">
            <button class="btn" onclick="addToCart('${p.id}')">Add to Cart</button>
            <button class="btn secondary" onclick="orderNow('${p.id}')">Order Now</button>
          </div>
        `;
        catalog.appendChild(card);

        // SEO data attributes are embedded for each product (for developer/SSR use)
        card.setAttribute('data-title', p.title);
        card.setAttribute('data-description', p.desc + ' — Price ₹' + p.price);
      });
      updateCategoryMeta(filterSize);
    }

    function updateCategoryMeta(size){
      // Update document title/meta description for simulated category pages
      if(!size){document.title='Shree Shyam Traders — Packaged Drinking Water Distributor';document.querySelector('meta[name=description]').setAttribute('content','Shree Shyam Traders - Wholesale & retail distributor of packaged drinking water. Trusted brands, pure water, fast delivery.');return}
      const map = {200:'200ml Bottles',500:'500ml Bottles',1000:'1 Litre Bottles',2000:'2 Litre Bottles'};
      const t = `Buy ${map[size]} — Shree Shyam Traders`;
      document.title = t;
      document.querySelector('meta[name=description]').setAttribute('content',`Buy ${map[size]} from trusted brands like Clear, Biofina & Mahi Aqua. Wholesale & retail pricing, fast delivery.`);
    }

    // init
    renderCatalog(200);

    // category tabs
    $all('.category-tab').forEach(btn=>btn.addEventListener('click', e=>{
      $all('.category-tab').forEach(x=>x.classList.remove('active'));
      btn.classList.add('active');
      const cat = parseInt(btn.getAttribute('data-cat'));
      renderCatalog(cat);
      window.location.hash = 'products-'+cat;
    }));

    // Cart functions
    function addToCart(id){
      const qtyInput = document.querySelector(`input.qty[data-id='${id}']`);
      const qty = qtyInput?Math.max(1,parseInt(qtyInput.value)||1):1;
      const product = PRODUCTS.find(p=>p.id===id);
      if(!product) return;
      if(cart[id]) cart[id].qty += qty; else cart[id] = {product, qty};
      showCartCount();
      renderCart();
      openCartModal();
    }

    function orderNow(id){
      const product = PRODUCTS.find(p=>p.id===id);
      const qtyInput = document.querySelector(`input.qty[data-id='${id}']`);
      const qty = qtyInput?Math.max(1,parseInt(qtyInput.value)||1):1;
      const text = `Hello Shree Shyam Traders, I'd like to order ${qty} x ${product.title} (Brand: ${product.brand}). Please provide a quote and delivery details.`;
      const url = `https://wa.me/919122422802?text=${encodeURIComponent(text)}`;
      window.open(url,'_blank');
    }

    function showCartCount(){
      const count = Object.values(cart).reduce((s,it)=>s+it.qty,0);
      const el = $('#cartCount');
      if(count>0){el.style.display='inline-block';el.textContent=count}else el.style.display='none';
    }

    function renderCart(){
      const body = $('#cartBody');
      body.innerHTML='';
      if(Object.keys(cart).length===0){body.innerHTML='<div style="color:var(--muted)">Your cart is empty.</div>';$('#cartTotal').textContent='₹0';return}
      let total=0;
      Object.entries(cart).forEach(([id,item])=>{
        const line = document.createElement('div');line.style.display='flex';line.style.justifyContent='space-between';line.style.alignItems='center';line.style.marginBottom='10px';
        line.innerHTML = `<div style="flex:1"><div style="font-weight:700">${item.product.title}</div><div style="color:var(--muted);font-size:13px">${item.product.brand} • ${item.product.size}ml</div></div><div style="text-align:right"><div style="font-weight:800">₹${item.product.price * item.qty}</div><div style="font-size:13px;color:var(--muted)">Qty: ${item.qty}</div></div>`;
        body.appendChild(line);
        total += item.product.price * item.qty;
      });
      $('#cartTotal').textContent = '₹' + total;
    }

    function toggleCart(){
      const modal = $('#cartModal');
      modal.classList.toggle('open');
    }
    function openCartModal(){
      $('#cartModal').classList.add('open');
    }

    $('#openCart').addEventListener('click',()=>{toggleCart();renderCart()});

    function clearCart(){cart={};showCartCount();renderCart();}

    function checkout(){
      if(Object.keys(cart).length===0){alert('Cart is empty. Add products to proceed.');return}
      // Build a message with order details and open WhatsApp/email
      let lines = ['New order from website:'];
      Object.values(cart).forEach(it=>{lines.push(`${it.qty} x ${it.product.title} (₹${it.product.price} each)`)});
      lines.push('Please confirm price & delivery.');
      const text = lines.join('\n');
      const wa = `https://wa.me/919122422802?text=${encodeURIComponent(text)}`;
      window.open(wa,'_blank');
    }

    function submitContact(e){
      e.preventDefault();
      const name = $('#c_name').value.trim();
      const phone = $('#c_phone').value.trim();
      const email = $('#c_email').value.trim();
      const msg = $('#c_msg').value.trim();
      // For demo: open mailto and WhatsApp. Replace with server call in production.
      const subject = encodeURIComponent('Contact form: ' + name);
      const body = encodeURIComponent(`Name: ${name}\nPhone: ${phone}\nEmail: ${email}\nMessage: ${msg}`);
      window.location.href = `mailto:orders@shreeshyamtraders.example?subject=${subject}&body=${body}`;
    }

    // Quick order modal
    function openQuickOrder(){document.getElementById('quickOrderModal').style.display='flex'}
    function closeQuickOrder(){document.getElementById('quickOrderModal').style.display='none'}
    function submitQuickOrder(e){
      e.preventDefault();
      const name = $('#q_name').value.trim();
      const phone = $('#q_phone').value.trim();
      const details = $('#q_details').value.trim();
      if(!phone){alert('Phone is required');return}
      const text = `Quick order from website:\nName: ${name}\nPhone: ${phone}\nOrder: ${details}`;
      const wa = `https://wa.me/919122422802?text=${encodeURIComponent(text)}`;
      window.open(wa,'_blank');
      closeQuickOrder();
    }

    // On page load: check hash to set category
    window.addEventListener('load',()=>{
      const hash = window.location.hash;
      if(hash && hash.startsWith('#products-')){
        const size = parseInt(hash.split('-')[1]);
        const tab = document.querySelector(`.category-tab[data-cat='${size}']`);
        if(tab) tab.click();
      }
    });
  </script>
</body>
</html>
