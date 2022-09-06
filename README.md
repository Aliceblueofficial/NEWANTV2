# NEWANTV2

the new API V2
ANTV2 Connect .Net library
The official .Net client for communicating with AliceBlue Connect API.

AliceBlue Connect is a set of REST-like APIs that expose many capabilities required to build a complete investment and trading platform. Execute orders in real time, manage user portfolio, stream live market data (WebSockets), and more, with the simple HTTP API collection.

Alice Blue Financial Services Pvt.Ltd. © 2022. Licensed under the MIT License.

# Requirements
ANTV2 Connect targets netstandard2.0. Minimum project target is .NET Framework 4.6.1 or .NET Core 2.0.

# Documentation
.Net Library
JSON API


#Install Client Library

Using NuGet
Execute in Tools » NuGet Package Manager » Package Manager Console

Install-Package ANTV2

# Getting started

// Import library

using ANTV2.ANTAPI;

// Initialize ANTV2 using userId and apiKey. Enabling Debug will give logs of requests and responses

            ANTNEWAPI.newapi1pushingdatafirsttarde("userid");   
            
            ANTNEWAPI.afterenkcryptionofdata("api_Key");
            
            // Example call for functions like "PlaceOrder"
            
            ANTNEWAPI.discqty = "1";
            ANTNEWAPI.trading_symbol = "BANKNIFTY22SEPFUT";
            ANTNEWAPI.exch = "NFO";
            ANTNEWAPI.transtype = "BUY";
            ANTNEWAPI.ret = "DAY";
            ANTNEWAPI.prctyp = "MIS";
            ANTNEWAPI.qty = "1";
            ANTNEWAPI.symbol_id = "37516";
            ANTNEWAPI.price = "39785.75";
            ANTNEWAPI.trigPrice = "39785.15";
            ANTNEWAPI.pCode = "I";
            ANTNEWAPI.complexty = "0";
            ANTNEWAPI.orderTag = "order1";
            ANTNEWAPI.aftersessionIDgenerationorderplacing();
						
						// Example call for functions like "squareofforder"
						
            ANTNEWAPI.squareofforderplacing();
						
					        // Example call for functions like "OrderBook"
							
            ANTNEWAPI.OrderBook();
						
						// Example call for functions like "TradeBook"
						
            ANTNEWAPI.TradeBook();
						
						// Example call for functions like "ModifyOrder"
						
            ANTNEWAPI.ModifyOrder();
						
						// Example call for functions like "CancelOrder"
						
            ANTNEWAPI.CancelOrder("220906000218300"); //nestOrderNumber  to be updated 
						
						// Example call for functions like "OrderHistory" 
						
            ANTNEWAPI.OrderHistory("220906000218300"); //nestOrderNumber  to be updated 
						
						// Example call for functions like "Holdings"
						
            ANTNEWAPI.Holdings();
						
					      // Example call for functions like "AccountDetails"
							
            ANTNEWAPI.AccountDetails();
						



        
    

