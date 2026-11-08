<html>
<body>
<h2>Shopping Cart</h2>

<h3>Register</h3>
<input id="u" placeholder="Username">
<input id="p" placeholder="Password">
<button onclick="reg()">Register</button>

<h3>Login</h3>
<button onclick="login()">Login</button>

<h3>Products</h3>
<button onclick="add(10000)">Mobile ₹10000</button>
<button onclick="add(40000)">Laptop ₹40000</button>

<h3 id="cart">Cart: ₹0</h3>

<script>
let user="", pass="", total=0;

function reg(){
user=u.value; pass=p.value;
alert("Registered");
}

function login(){
alert(u.value==user && p.value==pass ?
"Login Success":"Invalid Login");
}

function add(price){
total+=price;
cart.innerHTML="Cart: ₹"+total;
}
</script>
</body>
</html>
