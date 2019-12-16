attr_accessor:products
def initialize
    @name=name
    num = rand(100..999)
    lett =('A'..'Z').to_a.sample
    @id = lett+num.to_s
    @products ={}
end

def add_product(name,price,stock=1)
    if @products[name.downcase]
        @products[name.downcase][:stock]
        
        stock + 1
        
        return
    end
    product={price: price , stock:
    stock}
    @products[name.downcase] = product
    end

    def sale (num)
        num = num.to_f / 100.0
        @products.each do |key,val|
            val.each do |k,v|
                val[k] = v*num if k==:price
            end
        end
    end
    def stock (name)
        puts @products [name.downcase][:stock]
    end
    def purchase (name)
        @products [name.downcase] [:stock]
         -=1 if @products
        [name.downcase][:stock] > 0
    
    end

    def show_products ()
        puts "Our Products:"
        puts "----------"
    end
    shop= Shop.new("Supermarket")
    shop.add_product("Apples", 10, 5)
    shop.add_product("Bananas", 6, 2)
    shop.add_product("Apples", 10)
    shop.show_products


    shop.sale(50)

    shop.purchase("Bananas")

    shop.stock("Bananas")

    shop.show_products
     p shop.name

