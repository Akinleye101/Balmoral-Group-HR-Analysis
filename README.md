# Balmoral-Group-HR-Analysis

= Table.TransformColumnTypes(#"Promoted Headers",{{"Sheet 1: Summary Dashboard Data", type any}, {"Column2", type any}, {"Column3", type any}, {"Column4", type any}, {"Column5", type any}, {"Column6", type any}, {"Column7", type any}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Metric", type text}, {"Value", type any}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Category", type text}, {"Product Count", Int64.Type}, {"Avg Discount %", type number}, {"Avg Discount %_1", type number}, {"Avg Discounted Price (₹)", Int64.Type}, {"Total Reviews", Int64.Type}, {"Total Revenue (₹)", Int64.Type}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Rating", type any}, {"Product Count", Int64.Type}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Price Range", type text}, {"Product Count", Int64.Type}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Product Name", type text}, {"Avg Rating", type number}, {"Total Reviews", Int64.Type}, {"Total Reviews_1", Int64.Type}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Discount Range", type text}, {"Avg Rating", type number}})

= Table.TransformColumnTypes(Sheet1_Sheet,{{"Column1", type text}, {"Column2", type any}, {"Column3", type any}, {"Column4", type any}, {"Column5", type any}, {"Column6", type any}, {"Column7", type any}, {"Column8", type any}, {"Column9", type any}, {"Column10", type text}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Region", type any}, {"Department", type any}, {"Gender", type any}, {"Employee Count", type any}, {"Column5", type any}, {"Column6", type any}, {"Column7", type any}, {"Column8", type any}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Region", type text}, {"Department", type text}, {"Gender", type text}, {"Employee Count", Int64.Type}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Gender", type text}, {"Average Rating", type number}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Region", type text}, {"Department", type text}, {"Gender", type text}, {"Average Salary", Int64.Type}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Region", type text}, {"Compliance Status", type text}, {"Number Below 90K", Int64.Type}, {"Number Above 90K", Int64.Type}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Salary Band", type text}, {"Employee Count", Int64.Type}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Region", type text}, {"Salary Band", type text}, {"Employee Count", Int64.Type}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Performance Rating", type any}, {"Bonus % of Salary", type number}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Employee ID", type text}, {"Gender", type text}, {"Region", type text}, {"Salary", Int64.Type}, {"Rating", type number}, {"Bonus %", type number}, {"Bonus Amount", Int64.Type}, {"Total Pay", Int64.Type}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Region", type text}, {"Total Salary", Int64.Type}, {"Total Bonus", Int64.Type}, {"Total Payout", Int64.Type}})
= Table.TransformColumnTypes(#"Promoted Headers",{{"Region", type text}, {"Department", type text}, {"Gender", type text}, {"Employee Count", Int64.Type}})
