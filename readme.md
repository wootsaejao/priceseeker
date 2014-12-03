## PriceSeeker

This project is a failed cloning of [PriceGrabber](http://www.pricegrabber.com) (but a little bit functioning). 

I don't host it yet so it has to be run locally.

### Server Requirements
* PHP >= 5.4
* Mcrypt PHP extension


### Installation & Usage
```
git clone https://github.com/jowsingchue/priceseeker.git
cd priceseeker
```
Download dependencies
```
composer update
```
To run
```
php artisan serve
```
Then the site will be available at [http://localhost:8000](http://localhost:8000)


### Note
This project still only work with 
* [J-Force_Product_Web_Service](http://se.cpe.ku.ac.th/wiki/index.php/J-Force_Product_Web_Service).

Up coming
* [KU_Relationship](http://se.cpe.ku.ac.th/wiki/index.php/KU_Relationship)
* [Trekking_Webservice](https://github.com/Termchai/Trekking_Webservice)

Waiting for API improvement
* Find product by partial name
