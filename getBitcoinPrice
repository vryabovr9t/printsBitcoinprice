/**
 * Function to print the current Bitcoin price
 * 
 * @returns {number} The current Bitcoin price
 */
function getBitcoinPrice() {
    // Fetch the current Bitcoin price from an API
    const response = fetch('https://api.coindesk.com/v1/bpi/currentprice.json');
    const data = response.json();
    const price = data.bpi.USD.rate_float;
    
    // Print the current Bitcoin price
    console.log(price);
    
    // Return the current Bitcoin price
    return price;
}
