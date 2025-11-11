<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Growth Catalyst - Instagram Boost Services</title>
    <style>
        /* CSS STYLING */
        :root {
            --primary-color: #ff5733; /* A vibrant orange/red for focus */
            --secondary-color: #28a745; /* Green for success/growth */
            --bg-color: #f8f9fa;
            --text-color: #343a40;
            --card-bg: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background-color: var(--primary-color);
            color: white;
            padding: 20px 0;
            text-align: center;
            margin-bottom: 30px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        .section-title {
            text-align: center;
            margin-bottom: 20px;
            color: var(--primary-color);
            font-size: 2em;
            border-bottom: 3px solid var(--secondary-color);
            display: inline-block;
            padding-bottom: 5px;
            width: 100%;
        }

        .price-cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .card {
            background-color: var(--card-bg);
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.15);
        }

        .card h3 {
            color: var(--secondary-color);
            border-bottom: 2px solid #eee;
            padding-bottom: 10px;
            margin-top: 0;
        }

        .card ul {
            list-style: none;
            padding: 0;
        }

        .card li {
            padding: 8px 0;
            border-bottom: 1px dotted #ccc;
            display: flex;
            justify-content: space-between;
        }

        .card li:last-child {
            border-bottom: none;
        }

        /* Order Form Styling */
        .order-form-section {
            background-color: var(--card-bg);
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            margin-bottom: 40px;
        }

        .form-group {
            margin-bottom: 15px;
        }

        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
            color: var(--text-color);
        }

        input[type="text"],
        select {
            width: 100%;
            padding: 10px;
            border: 1px solid #ced4da;
            border-radius: 4px;
            box-sizing: border-box;
            font-size: 1em;
        }

        #total-price {
            font-size: 1.5em;
            font-weight: bold;
            color: var(--primary-color);
            display: block;
            margin-top: 10px;
        }

        .payment-box {
            background-color: #e9ecef;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            margin-top: 20px;
        }

        .upi-id {
            font-size: 1.2em;
            font-weight: bold;
            color: var(--secondary-color);
            margin-bottom: 10px;
            display: block;
        }

        .qr-code {
            max-width: 250px;
            height: auto;
            border: 5px solid white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin: 10px auto;
            display: block;
        }

        button {
            background-color: var(--primary-color);
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 1.1em;
            width: 100%;
            margin-top: 20px;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #d9482b;
        }

        .note {
            background-color: #fff3cd;
            color: #856404;
            padding: 15px;
            border-radius: 5px;
            margin-top: 20px;
            border: 1px solid #ffeeba;
            font-weight: bold;
        }

        .note strong {
            color: var(--primary-color);
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }
            .price-cards {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <h1>Growth Catalyst</h1>
            <p>🚀 Boost Your Instagram Presence Today!</p>
        </div>
    </header>

    <div class="container">
        <h2 class="section-title">✨ Our Instagram Boost Packages</h2>

        <div class="price-cards">
            <div class="card">
                <h3>Followers</h3>
                <ul>
                    <li><span>500 Followers</span> <span>₹25</span></li>
                    <li><span>1000 Followers</span> <span>₹50</span></li>
                    <li><span>5000 Followers</span> <span>₹250</span></li>
                </ul>
            </div>

            <div class="card">
                <h3>Likes</h3>
                <ul>
                    <li><span>500 Likes</span> <span>₹5</span></li>
                    <li><span>1000 Likes</span> <span>₹10</span></li>
                    <li><span>5000 Likes</span> <span>₹40</span></li>
                </ul>
            </div>

            <div class="card">
                <h3>Views</h3>
                <ul>
                    <li><span>500 Views</span> <span>₹10</span></li>
                    <li><span>1000 Views</span> <span>₹20</span></li>
                    <li><span>5000 Views</span> <span>₹60</span></li>
                </ul>
            </div>
        </div>

        <div class="order-form-section">
            <h2 class="section-title">🛒 Place Your Order & Pay</h2>

            <form id="orderForm">
                <div class="form-group">
                    <label for="profileHandle">Your Instagram Profile Handle:</label>
                    <input type="text" id="profileHandle" name="profileHandle" placeholder="@yourhandle" required>
                </div>

                <div class="form-group">
                    <label for="service">Select Service:</label>
                    <select id="service" name="service" required>
                        <option value="" disabled selected>--- Select a Service ---</option>
                        <option value="Followers_500">Followers - 500 (₹25)</option>
                        <option value="Followers_1000">Followers - 1000 (₹50)</option>
                        <option value="Followers_5000">Followers - 5000 (₹250)</option>
                        <option value="Likes_500">Likes - 500 (₹5)</option>
                        <option value="Likes_1000">Likes - 1000 (₹10)</option>
                        <option value="Likes_5000">Likes - 5000 (₹40)</option>
                        <option value="Views_500">Views - 500 (₹10)</option>
                        <option value="Views_1000">Views - 1000 (₹20)</option>
                        <option value="Views_5000">Views - 5000 (₹60)</option>
                    </select>
                </div>

                <div class="form-group">
                    <label>Total Amount to Pay:</label>
                    <span id="total-price">₹0</span>
                </div>

                <div class="payment-box">
                    <p>
                        **STEP 1: Make Your Payment**
                    </p>
                    <label>Scan the QR code or use the UPI ID below to pay the exact amount shown above.</label>
                    <span class="upi-id">UPI ID: niteshxalxo007@oksbi</span>
                    
                    
                    The QR code will be displayed below:
                    
                    

                    <div class="form-group" style="margin-top: 20px;">
                        <label for="utrNo">**STEP 2: Enter Payment UTR/Transaction Number (Compulsory):**</label>
                        <input type="text" id="utrNo" name="utrNo" placeholder="Enter 12-digit UTR/Transaction ID" required>
                    </div>
                </div>
                
                <div class="note">
                    <strong>IMPORTANT:</strong> After making the payment and entering the UTR, click the button below. A draft email will open—**just click send!** Your order will be processed only after payment is confirmed.
                </div>

                <button type="submit">STEP 3: Confirm Payment & Submit Order</button>
            </form>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const serviceSelect = document.getElementById('service');
            const totalPriceSpan = document.getElementById('total-price');
            const orderForm = document.getElementById('orderForm');

            // Map service values to prices
            const prices = {
                'Followers_500': 25,
                'Followers_1000': 50,
                'Followers_5000': 250,
                'Likes_500': 5,
                'Likes_1000': 10,
                'Likes_5000': 40,
                'Views_500': 10,
                'Views_1000': 20,
                'Views_5000': 60,
            };

            // Function to update the price
            function updatePrice() {
                const selectedService = serviceSelect.value;
                const price = prices[selectedService] || 0;
                totalPriceSpan.textContent = `₹${price}`;
            }

            // Event listener for service selection change
            serviceSelect.addEventListener('change', updatePrice);

            // Handle form submission
            orderForm.addEventListener('submit', function(e) {
                e.preventDefault();

                const profileHandle = document.getElementById('profileHandle').value.trim();
                const serviceValue = serviceSelect.value;
                const utrNo = document.getElementById('utrNo').value.trim();
                const amount = prices[serviceValue] || 0;
                
                // Get human-readable service name (e.g., "Followers - 1000")
                const serviceName = serviceSelect.options[serviceSelect.selectedIndex].text.replace(/\s\(.*\)/, '');

                if (!profileHandle || !serviceValue || !utrNo || amount === 0) {
                    alert('Please fill out all fields correctly, including the Payment UTR No., and select a service.');
                    return;
                }
                
                if (utrNo.length < 10) { // Basic check for UTR length
                    alert('Please enter a valid Payment UTR/Transaction Number.');
                    return;
                }

                // Construct the email body
                const subject = `New Order from Growth Catalyst: ${serviceName}`;
                const body = `
Dear Growth Catalyst,

I have just placed an order and completed the payment. Please confirm the details below:

* **Instagram Profile Handle:** ${profileHandle}
* **Service Ordered:** ${serviceName}
* **Amount Paid:** ₹${amount}
* **Payment UTR/Transaction No.:** ${utrNo}

Please process my order as soon as possible.

Thank you!
                `.trim();

                // Open the user's email client with pre-filled details
                const mailtoLink = `mailto:hiigrowthcatalyst@gmail.com?subject=${encodeURIComponent(subject)}&body=${encodeURIComponent(body)}`;
                window.location.href = mailtoLink;

                // Optional: Clear form after successful attempt to open mail client
                // orderForm.reset();
                // totalPriceSpan.textContent = '₹0';
            });
        });
    </script>

</body>
</html>
