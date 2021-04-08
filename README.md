
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

						Upbit Dealer ver.1.2.1

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

		IDE        :	Visual Studio 2019
		Language   :	c# Winform (.NET FrameWork)
		Include    :	upbit_API
		Require    :	Jwt package, json package

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

	Notice

		This project contain the latest version of upbit dealer. I stop to update bithumb dealer
		but upbit will be updated.


//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

	Precautions
	
		1. This DOES NOT solve everything. Eventually, the price goes up and then gain profit.

		2. I tring to do not make erros and test several times, but don't trust it entirely as
		there may be errors. So, DO NOT perform strange manipulations, which increases the
		possibility of errors. That is a useless act and only your damage will occur.
	
		3. Characteristic of upbit api is it returns accurate results, but the number of requests
		per second is very low. Api limit are based on ip address and account. So DO NOT open
		'trader' and many 'chart' at the same time.

		4. Upbit api always need access ip address and your ip address sometimes change. That
		means, if you can not login one day, check your current ip address and change the access
		ip address in upbit homepage.

		5. Upbit has a large fluctuation range in the short term. So, the short-term yield is
		high. The reason seems that upbit has many beginners.


//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


	Can List

		1. Can show graph using API candle data

		2. Can trade (order or cancel)

		3. can lockup trade history

		4. Can use macro with bollinger value for top 70 coin

		5. Can show average weighted and average bollinger value


//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

	Update

		1. change the algorithm of api load, therefore it can execute macro more faster and open
		more chart at the same time

		2. reduce gc rate

		
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

	How to build

		1. before build with visual studio, install package

		2. and build

		2. or install with 'UpbitDealer_setup.msi' file 


//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

	How to Use


		1. 


//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
