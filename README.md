# CAT
Tiệm bán hàng len, sản phẩm, phụ kiện len và blind box thần tượng
lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Store CAT — Shop & Quản lý</title>
<style>
:root{--pink:#ffd9e8;--pink2:#fff0f6;--lav:#eadfff;--blue:#dff3ff;--cream:#fffaf6;--text:#514951;--accent:#d77fa5;--dark:#76546a}
*{box-sizing:border-box}body{margin:0;font-family:Arial,sans-serif;background:var(--cream);color:var(--text)}button,input,select,textarea{font:inherit}button{cursor:pointer;border:0}.top{position:sticky;top:0;z-index:20;background:#fffaf6ee;backdrop-filter:blur(12px);border-bottom:1px solid #efdee6}.nav{max-width:1150px;margin:auto;padding:13px 18px;display:flex;align-items:center;justify-content:space-between;gap:12px}.logo{font-size:24px;font-weight:900;color:var(--dark)}.navlinks{display:flex;gap:18px}.navlinks button{background:none;color:#665961;font-weight:800}.pill{background:white;border:1px solid #ead8e1;padding:9px 14px;border-radius:999px;color:#8b5570;font-weight:900}.hero{max-width:1150px;margin:22px auto;padding:18px}.heroBox{background:linear-gradient(120deg,var(--pink),var(--lav),var(--blue));border-radius:30px;padding:42px;display:flex;justify-content:space-between;align-items:center}.hero h1{font-size:clamp(38px,7vw,68px);line-height:1;margin:0 0 12px;color:#634e5b}.hero p{max-width:550px;font-size:17px}.cat{font-size:105px}.section{max-width:1150px;margin:auto;padding:18px}.head{display:flex;justify-content:space-between;align-items:center;gap:12px;margin-bottom:16px}.head h2{margin:0}.filters{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:17px}.filter{background:white;border:1px solid #eadde3;padding:8px 13px;border-radius:999px;font-weight:800;color:#756872}.filter.active{background:#f6c8dc;color:#77455d}.grid{display:grid;grid-template-columns:repeat(4,1fr);gap:16px}.card{background:white;border:1px solid #f0e0e6;border-radius:21px;overflow:hidden;box-shadow:0 8px 22px #9c718b12}.pic{height:190px;display:flex;align-items:center;justify-content:center;font-size:70px;background:var(--pink2)}.pic.blue{background:#eef9ff}.pic.lav{background:#f4efff}.pic.yellow{background:#fff7df}.info{padding:14px}.tag{font-size:10px;font-weight:900;color:#b25c82;text-transform:uppercase}.name{font-weight:900;margin:4px 0}.price{font-weight:900;color:#b04e78}.stock{font-size:12px;color:#8d8188;margin-top:4px}.add{width:100%;margin-top:11px;padding:10px;border-radius:12px;background:#f8d6e5;color:#7d4a62;font-weight:900}.about{margin:22px 0 35px;background:linear-gradient(120deg,#fff0f6,#f2ecff);padding:28px;border-radius:26px}.admin{display:none}.admin.on{display:block}.shop.hidden{display:none}.panel{background:white;border:1px solid #eadfe4;border-radius:22px;padding:20px;margin-bottom:18px}.tabs{display:flex;gap:8px;margin-bottom:15px}.tab{padding:9px 14px;border-radius:999px;background:#f8edf2;font-weight:900;color:#765766}.tab.active{background:#d98bad;color:#fff}.formgrid{display:grid;grid-template-columns:1fr 1fr;gap:12px}.field{display:flex;flex-direction:column;gap:6px}.field.full{grid-column:1/-1}.field input,.field select,.field textarea{padding:11px;border:1px solid #e4d8de;border-radius:12px;outline:none;background:#fff}.field textarea{min-height:90px;resize:vertical}.save{background:#d78aaa;color:white;padding:11px 17px;border-radius:12px;font-weight:900;margin-top:12px}..cancel{background:#f4e9ee;color:#765766;padding:11px 17px;border-radius:12px;font-weight:900;margin:12px 0 0 7px}.adminList{display:grid;gap:10px}.adminItem{display:flex;align-items:center;gap:12px;border:1px solid #eee2e7;padding:10px;border-radius:15px}.thumb{width:55px;height:55px;border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:28px;background:#fff0f6}.adminInfo{flex:1}.actions{display:flex;gap:6px}.mini{padding:8px 10px;border-radius:9px;background:#f6e9ee;color:#765766;font-weight:800}.danger{background:#ffe2e5;color:#a44c58}.cartModal{display:none;position:fixed;inset:0;background:#43343d66;z-index:50;align-items:center;justify-content:center;padding:15px}.cartModal.show{display:flex}.modal{width:min(560px,100%);max-height:90vh;overflow:auto;background:#fffafc;border-radius:23px;padding:22px}.modalTop{display:flex;justify-content:space-between}.close{width:35px;height:35px;border-radius:50%;background:#f4e6ed}.cartrow{display:flex;justify-content:space-between;gap:10px;padding:12px 0;border-bottom:1px solid #eee}.qty button{width:27px;height:27px;border-radius:7px;background:#f6dce7}.total{display:flex;justify-content:space-between;font-size:19px;font-weight:900;margin:17px 0}.checkout{width:100%;padding:13px;background:#d78aaa;color:#fff;border-radius:13px;font-weight:900}.login{position:fixed;inset:0;background:#43343d66;z-index:60;display:none;align-items:center;justify-content:center;padding:18px}.login.show{display:flex}.loginBox{background:white;padding:25px;border-radius:22px;width:min(380px,100%)}.loginBox input{width:100%;padding:11px;border:1px solid #ddd;border-radius:11px;margin:7px 0 12px}.notice{background:#fff5d9;border-radius:13px;padding:10px;margin-bottom:12px;font-size:13px}.empty{text-align:center;padding:28px;color:#9a8e95}footer{text-align:center;padding:28px;background:#f8e8ef;color:#806b75;margin-top:25px}
@media(max-width:850px){.grid{grid-template-columns:repeat(2,1fr)}.cat{font-size:70px}.formgrid{grid-template-columns:1fr}.field.full{grid-column:auto}}
@media(max-width:560px){.navlinks{display:none}.heroBox{padding:30px 23px}.cat{font-size:55px}.grid{gap:10px}.pic{height:150px;font-size:55px}.section{padding:14px}.adminItem{align-items:flex-start}.actions{flex-direction:column}}
</style>
</head>
<body>
<header class="top"><div class="nav">
<div class="logo">🐱 STORE CAT</div>
<div class="navlinks"><button onclick="showShop()">Trang chủ</button><button onclick="scrollToProducts()">Sản phẩm</button><button onclick="openAdminLogin()">⚙ Quản lý</button></div>
<button class="pill" onclick="openCart()">🛒 Giỏ hàng <b id="count">0</b></button>
</div></header>

<div id="shop" class="shop">
<section class="hero"><div class="heroBox"><div><h1>Welcome to<br>Store CAT 🐾</h1><p>Góc nhỏ pastel dành cho người yêu len, handmade và blind box / idol order.</p><button class="pill" onclick="scrollToProducts()">Khám phá sản phẩm ✨</button></div><div class="cat">🐱</div></div></section>
<section class="section" id="products"><div class="head"><div><h2>Sản phẩm</h2><small>Chọn món bạn thích rồi thêm vào giỏ 💗</small></div></div>
<div class="filters"><button class="filter active" onclick="filter('all',this)">Tất cả</button><button class="filter" onclick="filter('yarn',this)">🧶 Len sợi</button><button class="filter" onclick="filter('idol',this)">🎀 Blind Box / Idol</button></div>
<div class="grid" id="productGrid"></div></section>
<section class="section"><div class="about"><h2>🐾 Store CAT</h2><p>Website bán hàng pastel cute. Bạn có thể tự thêm, sửa, xóa sản phẩm trong khu quản lý. Dữ liệu của bản demo được lưu trên trình duyệt này.</p></div></section>
</div>

<div id="admin" class="admin">
<section class="section"><div class="head"><div><h2>⚙ Quản lý Store CAT</h2><small>Thêm và chỉnh sửa sản phẩm</small></div><button class="pill" onclick="showShop()">← Về shop</button></div>
<div class="notice">💡 Đây là bản quản lý chạy trực tiếp trên trình duyệt. Nếu muốn dữ liệu đồng bộ cho nhiều điện thoại/máy tính và khách đặt hàng từ Internet, bước tiếp theo cần kết nối cơ sở dữ liệu + hosting.</div>
<div class="tabs"><button class="tab active" onclick="adminTab('products',this)">🧶 Sản phẩm</button><button class="tab" onclick="adminTab('orders',this)">📦 Đơn hàng</button></div>
<div id="productAdmin" class="panel">
<h3 id="formTitle">➕ Thêm sản phẩm</h3>
<div class="formgrid">
<div class="field"><label>Tên sản phẩm</label><input id="pname" placeholder="VD: Len nhung pastel"></div>
<div class="field"><label>Giá (VNĐ)</label><input id="pprice" type="number" placeholder="35000"></div>
<div class="field"><label>Danh mục</label><select id="ptype"><option value="yarn">🧶 Len sợi</option><option value="idol">🎀 Blind Box / Idol</option></select></div>
<div class="field"><label>Tồn kho</label><input id="pstock" type="number" value="10"></div>
<div class="field"><label>Biểu tượng tạm (nếu chưa có ảnh)</label><input id="pemoji" value="🧶"></div>
<div class="field"><label>Màu nền</label><select id="pbg"><option value="pink">Hồng pastel</option><option value="blue">Xanh baby</option><option value="lav">Tím lavender</option><option value="yellow">Kem vàng</option></select></div>
<div class="field full"><label>Mô tả</label><textarea id="pdesc" placeholder="Mô tả sản phẩm..."></textarea></div>
</div>
<button class="save" onclick="saveProduct()">💾 Lưu sản phẩm</button><button class="cancel" onclick="resetForm()">Hủy</button>
</div>
<div id="productListPanel" class="panel"><h3>Danh sách sản phẩm</h3><div class="adminList" id="adminList"></div></div>
<div id="ordersPanel" class="panel" style="display:none"><h3>📦 Đơn hàng</h3><div id="ordersList" class="empty">Chưa có đơn hàng.</div></div>
</section></div>

<div class="cartModal" id="cartModal"><div class="modal"><div class="modalTop"><h2>🛒 Giỏ hàng</h2><button class="close" onclick="closeCart()">×</button></div><div id="cartList"></div><div class="total"><span>Tổng cộng</span><span id="total">0₫</span></div><button class="checkout" onclick="placeOrder()">Đặt hàng</button></div></div>

<div class="login" id="login"><div class="loginBox"><h2>🔐 Quản lý Store CAT</h2><p>Nhập mật khẩu quản lý.</p><input id="password" type="password" placeholder="Mật khẩu"><button class="save" style="width:100%" onclick="loginAdmin()">Đăng nhập</button><button class="cancel" style="width:100%;margin-left:0" onclick="closeLogin()">Hủy</button><small>Mật khẩu demo: <b>storecat123</b></small></div></div>

<footer>🐱 STORE CAT · Pastel little shop · Made with love ♡</footer>

<script>
const defaultProducts=[
{id:1,name:'Len nhung pastel',price:35000,type:'yarn',stock:20,emoji:'🧶',bg:'pink',desc:'Len nhung mềm, phù hợp móc thú bông.'},
{id:2,name:'Len cotton milk',price:42000,type:'yarn',stock:15,emoji:'🧶',bg:'blue',desc:'Len cotton dễ móc, màu pastel.'},
{id:3,name:'Len milk cotton',price:39000,type:'yarn',stock:18,emoji:'🧵',bg:'lav',desc:'Dòng len nhẹ, nhiều màu.'},
{id:4,name:'Set len mini cute',price:59000,type:'yarn',stock:10,emoji:'🎨',bg:'yellow',desc:'Set nhiều màu cho đồ handmade.'},
{id:5,name:'Blind Box Idol — Series A',price:189000,type:'idol',stock:8,emoji:'🎁',bg:'pink',desc:'Blind box idol — hàng order.'},
{id:6,name:'Blind Box Idol — Series B',price:219000,type:'idol',stock:7,emoji:'🧸',bg:'blue',desc:'Blind box idol — hàng order.'},
{id:7,name:'Idol Order — Photocard',price:99000,type:'idol',stock:12,emoji:'💌',bg:'lav',desc:'Nhận order photocard theo đợt.'},
{id:8,name:'Idol Merchandise Order',price:259000,type:'idol',stock:5,emoji:'✨',bg:'yellow',desc:'Nhận order merchandise thần tượng.'}
];
let products=JSON.parse(localStorage.getItem('storecat_products')||'null')||defaultProducts;
let cart=JSON.parse(localStorage.getItem('storecat_cart')||'[]');
let orders=JSON.parse(localStorage.getItem('storecat_orders')||'[]');
let editId=null;
const money=n=>Number(n).toLocaleString('vi-VN')+'₫';
function saveData(){localStorage.setItem('storecat_products',JSON.stringify(products));localStorage.setItem('storecat_cart',JSON.stringify(cart));localStorage.setItem('storecat_orders',JSON.stringify(orders))}
function render(list=products){document.getElementById('productGrid').innerHTML=list.length?list.map(p=>`<article class="card"><div class="pic ${p.bg}">${p.emoji}</div><div class="info"><div class="tag">${p.type==='yarn'?'Len sợi':'Blind Box / Idol'}</div><div class="name">${p.name}</div><div class="price">${money(p.price)}</div><div class="stock">${p.stock>0?'Còn '+p.stock+' sản phẩm':'Hết hàng'}</div><button class="add" ${p.stock<=0?'disabled':''} onclick="addToCart(${p.id})">+ Thêm vào giỏ</button></div></article>`).join(''):'<div class="empty">Chưa có sản phẩm.</div>'}
function filter(type,btn){document.querySelectorAll('.filter').forEach(x=>x.classList.remove('active'));btn.classList.add('active');render(type==='all'?products:products.filter(p=>p.type===type))}
function scrollToProducts(){document.getElementById('products').scrollIntoView({behavior:'smooth'})}
function showShop(){document.getElementById('shop').classList.remove('hidden');document.getElementById('admin').classList.remove('on');window.scrollTo(0,0)}
function openAdminLogin(){document.getElementById('login').classList.add('show')}
function closeLogin(){document.getElementById('login').classList.remove('show')}
function loginAdmin(){if(document.getElementById('password').value==='storecat123'){closeLogin();document.getElementById('shop').classList.add('hidden');document.getElementById('admin').classList.add('on');renderAdmin();window.scrollTo(0,0)}else alert('Sai mật khẩu nha 🐱')}
function adminTab(which,btn){document.querySelectorAll('.tab').forEach(x=>x.classList.remove('active'));btn.classList.add('active');document.getElementById('productAdmin').style.display=which==='products'?'block':'none';document.getElementById('productListPanel').style.display=which==='products'?'block':'none';document.getElementById('ordersPanel').style.display=which==='orders'?'block':'none';if(which==='orders')renderOrders()}
function saveProduct(){let name=document.getElementById('pname').value.trim(),price=Number(document.getElementById('pprice').value),stock=Number(document.getElementById('pstock').value);if(!name||!price){alert('Vui lòng nhập tên và giá sản phẩm.');return}let data={name,price,stock:Math.max(0,stock),type:document.getElementById('ptype').value,emoji:document.getElementById('pemoji').value||'🐱',bg:document.getElementById('pbg').value,desc:document.getElementById('pdesc').value};if(editId){products=products.map(p=>p.id===editId?{...p,...data}:p)}else{data.id=Date.now();products.unshift(data)}saveData();resetForm();renderAdmin();render();alert(editId?'Đã cập nhật sản phẩm 💗':'Đã thêm sản phẩm 💗')}
function resetForm(){editId=null;document.getElementById('formTitle').textContent='➕ Thêm sản phẩm';['pname','pprice','pdesc'].forEach(id=>document.getElementById(id).value='');document.getElementById('pstock').value=10;document.getElementById('pemoji').value='🧶';document.getElementById('ptype').value='yarn';document.getElementById('pbg').value='pink'}
function editProduct(id){let p=products.find(x=>x.id===id);editId=id;document.getElementById('formTitle').textContent='✏️ Chỉnh sửa sản phẩm';document.getElementById('pname').value=p.name;document.getElementById('pprice').value=p.price;document.getElementById('ptype').value=p.type;document.getElementById('pstock').value=p.stock;document.getElementById('pemoji').value=p.emoji;document.getElementById('pbg').value=p.bg;document.getElementById('pdesc').value=p.desc||'';window.scrollTo({top:250,behavior:'smooth'})}
function deleteProduct(id){if(confirm('Xóa sản phẩm này?')){products=products.filter(p=>p.id!==id);cart=cart.filter(x=>x.id!==id);saveData();renderAdmin();render();updateCart()}}
function renderAdmin(){document.getElementById('adminList').innerHTML=products.map(p=>`<div class="adminItem"><div class="thumb">${p.emoji}</div><div class="adminInfo"><b>${p.name}</b><br><small>${money(p.price)} · Tồn: ${p.stock} · ${p.type==='yarn'?'Len':'Idol'}</small></div><div class="actions"><button class="mini" onclick="editProduct(${p.id})">Sửa</button><button class="mini danger" onclick="deleteProduct(${p.id})">Xóa</button></div></div>`).join('')||'<div class="empty">Chưa có sản phẩm.</div>'}
function renderOrders(){if(!orders.length){document.getElementById('ordersList').innerHTML='<div class="empty">Chưa có đơn hàng.</div>';return}document.getElementById('ordersList').innerHTML=orders.map(o=>`<div class="adminItem"><div class="adminInfo"><b>Đơn #${o.id}</b><br><small>${o.items.map(i=>i.name+' × '+i.qty).join(', ')}</small><br><b>${money(o.total)}</b> · ${o.date}</div></div>`).join('')}
function addToCart(id){let p=products.find(x=>x.id===id),x=cart.find(x=>x.id===id);if(!p||p.stock<=0)return alert('Sản phẩm đã hết hàng.');if(x){if(x.qty>=p.stock)return alert('Không thể thêm quá số lượng tồn kho.');x.qty++}else cart.push({id,qty:1});saveData();updateCart();openCart()}
function updateCart(){document.getElementById('count').textContent=cart.reduce((s,x)=>s+x.qty,0);let el=document.getElementById('cartList');if(!cart.length){el.innerHTML='<div class="empty">Giỏ hàng đang trống 🐾</div>';document.getElementById('total').textContent='0₫';return}el.innerHTML=cart.map(x=>{let p=products.find(p=>p.id===x.id);return `<div class="cartrow"><div><b>${p.name}</b><br><small>${money(p.price)} × ${x.qty}</small></div><div class="qty"><button onclick="changeQty(${x.id},-1)">−</button> ${x.qty} <button onclick="changeQty(${x.id},1)">+</button></div></div>`}).join('');document.getElementById('total').textContent=money(cart.reduce((s,x)=>s+products.find(p=>p.id===x.id).price*x.qty,0))}
function changeQty(id,n){let x=cart.find(i=>i.id===id),p=products.find(i=>i.id===id);if(n>0&&x.qty>=p.stock)return;if(x){x.qty+=n;if(x.qty<=0)cart=cart.filter(i=>i.id!==id)}saveData();updateCart()}
function openCart(){document.getElementById('cartModal').classList.add('show');updateCart()}
function closeCart(){document.getElementById('cartModal').classList.remove('show')}
function placeOrder(){if(!cart.length)return alert('Giỏ hàng đang trống.');let total=cart.reduce((s,x)=>s+products.find(p=>p.id===x.id).price*x.qty,0);let order={id:Date.now().toString().slice(-6),date:new Date().toLocaleString('vi-VN'),items:cart.map(x=>{let p=products.find(p=>p.id===x.id);return {name:p.name,qty:x.qty}}),total};orders.unshift(order);products=products.map(p=>{let x=cart.find(x=>x.id===p.id);return x?{...p,stock:p.stock-x.qty}:p});cart=[];saveData();updateCart();closeCart();render();alert('Đã tạo đơn demo #'+order.id+' 💗\\nBản tiếp theo có thể thêm form tên, SĐT, địa chỉ và gửi đơn về cho bạn.')}
render();updateCart();
</script>
</body>
</html>
