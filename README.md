# Stock-and-Company-Identifiers-API
Through <a href="https://tradefeeds.com/stock-and-company-identifiers-api/
" rel="nofollow"> Tradefeeds Stock and Company Identifiers API</a> customers retrive all necessary stock and company identifiers including stock ticker symbols,CIK codes, employee ID, ISIN and CUSIP numbers. We provide data on more than 7000 publicly traded companies in the United States. Instead of engaging in an arduos search of data yourself or maintaining an in-house database, you can rapidly obtain accurate data for a considerable number of companies. The data is retrieved through fast and seamless JSON REST API or in downloadable excel or csv files. 

Tradefeeds' customers have a diverse background - from developers who build their applications for a specific audience to in-house teams in all-sized companiesb and entrepeneurial individuals. Tradefeeds subscription packages are developed in such a way to serve all customers' needs. For the moment, there is no free trial provided. In case that you are a researcher or a student, we could negotiate a free trial. <a href="https://tradefeeds.com/pricing-subscription-plans/" rel="nofollow">Sign up for an API key</a> and we work out your case.

<h2><a id="user-content-api-features" class="anchor" href="https://github.com/Tradefeeds-Financial-data-API/Company-information-API#api-features" aria-hidden="true"></a>API Features</h2>

<li><strong>Stock Ticker Symbol</strong></li>
<li><strong>CIK code</strong></li>
<li><strong>Employee ID</strong></li>
<li><strong>ISIN number</strong></li>
<li><strong>CUSIP number</strong></li>

<h2><a id="user-content-ways-to-access-company-data" class="anchor" href="https://github.com/Tradefeeds-Financial-data-API/Company-information-API#ways-to-access-stock-and-company-identifiers-data" aria-hidden="true"></a>Ways to access stock and company identifiers data</h2>
<ul>
 	<li><strong>JSON REST API</strong></li>
 	<li><strong>Excel CSV download</strong></li>
 	<li><strong>PDF reports</strong></li>
 	<li><strong>Email link</strong></li>
</ul>

<h2>Documentation</h2>

Our <a href="https://tradefeeds.com/api-documentation/" rel="nofollow"> documentation</a>  includes input API filtering parameters, output response objects with explanation of their meaning. Clear request and response examples are given on the documentation page. Furthermore, we provide SDKs for Javascript, JQuery, VueJS, Angular, JAVA, PHP, NodeJS, Python, Go, Ruby, C#, R, Strest, Rust, Swift and Scala

<h2>Request and response examples</h2>

<p><a href="https://tradefeeds.com/api-documentation/">https://tradefeeds.com/api/v1/identifiers
    ?key=YOUR-KEY
        &stock_ticker_symbol=aapl</a></p>



    "status": {
        "message": "Success"
    },
    "results": [
        {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "cik_code": "0000320193"
            "cusip_number": "037833100"
            "employer_id": "942404110"
            "exchange": "nasdaq"
            "ipo_date": "1980:11:12"
            "founded_date": "1976:04:01"
            "industry": "technology"
            "sector": "consumer electronics"
        }
    [


The API is filtered for each identifier in order to obtain data on the stock and company identifiers you are interested in. 



<h2>Customer support</h2>

In case that you encounter a data issue or you want to have more features added to the API, please contact us at support@tradefeeds.com. 

<h2>Legal</h2>

<p> The use of Tradefeeds proprietary data and API database is subject to the&nbsp;<a href="https://tradefeeds.com/terms-and-conditions-on-data/">Tradefeeds Terms &amp; Conditions.</a></p>

















