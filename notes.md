# create Store then create slice 
# Slice take object with 3 parameter
# every slice has name ,initial step and reducer
# reducer take two argument, state and action
# state is current state of slice and action is the other argument or props passed to be used in function/methods
# we have to manually export the Slicer/reducer functionality using slicer_name.actions
# then we have to export the reducer using Slicer_name.reducer
# then import the reducer in store(inside the store)
# inorder to run the functionality use the useDispath() with argument required
# inorder to selct the state from the store use the useSelector()
# then import the provider and the store which similar to provider and the value in context api , where value is nothing but store where we have to pass store name as value in main.jsx
