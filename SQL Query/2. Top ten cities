select c.city , sum(amount) as total_sales
from customers c
join
payments p on c.customerNumber= p.customerNumber
group by 1
order by total_sales desc
limit 10;
