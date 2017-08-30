# Mako Templates / EdX render_to_response() method. 
# Django version 1.8

render_to_response() can only send 1 dictionary to the webpage. If sent more than 1 dict, one of them would be mako.runtime.undefined which would lead to an error when reading this variable.
