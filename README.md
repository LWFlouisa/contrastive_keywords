# contrastive_keywords
A proposal for contrastive language for declarative and procedural programming.

## Contrastive Ruby
But in this context would replace elsif but used only once. But can be extended with But if.

That would point to a specific string in a Yoda conditional.

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

## Borrowing from French contrastive language
This prevents butt hat contrastive language, but borrowing contrastive language from Francais.

~~~fruby
cette      ( translates to that )
mais       ( translates to butt )
mais cette ( condensed to maisette, which in this context isn't "little house" )

cette        "greyerre" == le_fromage
maisette non "bre"      == le fromage
fin
~~~
