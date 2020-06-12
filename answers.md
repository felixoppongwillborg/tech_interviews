person = 'Felix' 
'Felix' => 'string'
Numbers.
Strings.
Symbols.
Hashes.
Arrays.
Booleans.

2.7.0 :001 > car_1 = { wheels: 4, max_speed: 60, color: 'red' }
2.7.0 :002 > car_1 [0]
 => nil 
2.7.0 :003 > car_1
 => {:wheels=>4, :max_speed=>60, :color=>"red"} 
2.7.0 :004 > car_2 = {wheels: 3, max_speed: 100, color: 'blue' }
2.7.0 :005 > cars = [car_1, car_2]
2.7.0 :006 > cars
 => [{:wheels=>4, :max_speed=>60, :color=>"red"}, {:wheels=>3, :max_speed=>100, :color=>"blue"}] 
2.7.0 :007 > cars [1]
 => {:wheels=>3, :max_speed=>100, :color=>"blue"} 
2.7.0 :008 > car_2 [ :color ]
 => "blue" 