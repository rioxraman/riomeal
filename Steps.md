1. Categories Screen

<Stack.Screen name="MealsOverview" component={MealsOverviewScreen} 
           options={
            ({route,navigation}) => {
              const catId = route.params.categoryId;;
              return {
                title:catId
              }
            }
          } />