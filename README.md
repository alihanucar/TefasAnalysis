# Turkiye Electronic Fund Trading Platform - TEFAS

TEFAS is an electronic fund platform in Turkiye that allows to compare all funds over a single system and to reach all funds in the market with a single investment account. Here is the [Link](https://www.tefas.gov.tr/). I intend to integrate various functions that will offer distinctive insights and analysis of the funds.

## 1) cashflow_fund() function:

I have developed a ***cashflow_fund*** function utilizing historical data from TEFAS to calculate the cash flow of mutual and pension funds, in order to gain a comprehensive understanding of the funds' real growth. To utilize the script, it is necessary to download historical data from the TEFAS website and upload it as a "tefasveriler.csv" file to your directory. The script will then proceed to calculate daily cash flow and store it in a new column, obtaining a cumulative summation at the conclusion of the specified term. The script also includes the capability to display a plot of daily changes, and the dates can be easily modified within the script.

What is the difference between AuM change and cash flow?

Cash flow in funds refers to the inflows and outflows of cash that are associated with a particular fund. This can include cash that is invested into the fund by investors, as well as cash that is withdrawn from the fund by investors or used to make investments. The net cash flow for a fund over a given period of time can provide insight into how investors are viewing the fund and whether they are becoming more or less interested in investing in it.

AUM (Assets Under Management) differences of the funds refers to the change in the total value of assets that a fund is managing. This can include investments in stocks, bonds, real estate, and other assets. AUM changes can provide insight into how well a fund is performing and whether it is growing or shrinking in size. AUM differences can be calculated by subtracting the starting AUM from the ending AUM over a certain period of time.

In summary, cash flow in funds gives information about the cash inflows and outflows to the fund while AUM differences gives information about the change in the value of assets managed by the fund.

![Logo](https://www.tefas.gov.tr/Images/tefas_web_site_logo_TR_Bilgilendirme.png)
