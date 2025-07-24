function calculateDiscountedPrice(price, discount) {
    if (discount >= 20) {
        var discountprice = price * (discount / 100);
        return price - discountprice;
    }
    else {
        return price;
    }
}

# Input from user
original_price = float(input("Enter the original price of the item: "));
discount_percent = float(input("Enter the discount percentage: "));

# Calculation of final price
final_price = calculateDiscount(original_price, discount_percent);

# Show result
if discount_percent >= 20: 
    print("Discount applied! Final price: %.2f" % final_price) 
else: 
    print("No discount applied. Final price: %.2f" % final_price)# goddy-python-assigment
