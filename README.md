# contrastive_keywords
A proposal for contrastive language for declarative and procedural programming.

## But, in this context, would be an alternative to elsif in this case.

~~~ruby
the_fruit = "green apple"

if    not "green apple"   == the_fruit; puts ">> This is an orange tomato."
elsif not "orange tomato" == the_fruit; puts ">> This is a green apple."
else
  puts ">> I have no idea what this fruit is."
end
~~~

## Equivalent in prolog.

~~~prolog
object(X).
object(fruit).

fruit(orange_tomato, not_apple) :- object(fruit).
fruit(green_apple, not_orange)  :- obhect(fruit).
~~~
