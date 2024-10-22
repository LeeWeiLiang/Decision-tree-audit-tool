# Decision-tree-audit-to
Dynamic creatives provide personalized and data-driven content, leading to overall improved performances.
Its requireds accurate setups to ensure that a variety of creatives can be served to each placement based on optimised rulings/AB testing by the advertiser.
It is therefore important to ensure that the creatives are serving the correct market, you wouldn't want to serve a creative/ad in mandarin to a viewer of another country that can't understand it.
Using the formula TRANSPOSE(FILTERXML()) to separate the placement taxonomy name into different columns based on the underscore delimiter, we are then able to audit all the placements using dynamic creatives at once. (upto 20k rows)

<ins>Matching the market:</ins>

Decision tree name = xyz_**AU**_7_30_24    >  placement name = xyz_xyz_etc.._**AU**_xyz_xyz
