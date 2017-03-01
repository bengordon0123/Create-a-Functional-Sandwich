#Ham and turkey sandwiches



def pepare_and_serve():

    print('Get two slices of bread')

    print('Spread with mayo, mustard, or ketchup')

    print('Spread cheese')
    print(‘Add meat’)

    print('Add additional toppings')

    print('Cut the sandwich down the middle’)
    print(‘Serve on a plate’)




def ham_sandwich(ingredient):

    pepare_and_serve()

    ham_sandwich = 'A {} sandwich'.format(ingredient)

    return ham_sandwich




def turkey_sandwich(*ingredients):

    prepare_and_serve()

    turkey_sandwich = 'a turkey sandwich {} ingredients'.format(len(ingredients))

    return turkey_sandwich

        

# make a ham sandwich

print(ham_sandwich('ham'))




# make a turkey sandwich

print(turkey_sandwich(‘turkey'))

