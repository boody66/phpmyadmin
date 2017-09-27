CREATE TABLE `items_for_sale` (
 `id` int(11) NOT NULL AUTO_INCREMENT,
 `item_name` varchar(250) NOT NULL,
 `item_price` decimal(8,2) NOT NULL,
 `image_addr` varchar(500) NOT NULL,
 `created_at` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
 PRIMARY KEY (`id`),
 UNIQUE KEY `item_name` (`item_name`)
) ENGINE=InnoDB AUTO_INCREMENT=13 DEFAULT CHARSET=latin1
