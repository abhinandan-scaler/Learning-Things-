## Create a route component 

- For creating a route like `/attempt` in interviewbit.
- Go to --> `config/routes/interviewbit.rb` [for scaler go to `config/routes/scaler.rb`]

- Now create a route for `attempt` in the file with a method called on `attempt_controller`.

- Create route like `get '/attempt' => attempt#index` where index is the first function that is called.

- Now generate a controller by running a command `rails g controller Attempt` with CamelCase format of controller.

- Now in the `controller` a file `attempt_controller.rb` will be there.

**Write this for basic working of page**
```rb
class AttemptController < ApplicationController
    layout 'frontend'
    def index
    end
end

```
- In the `views` folder a folder named `attempt` is created.

- Create an `index.erb` file inside it and use it for dispalying things.

> That's all 