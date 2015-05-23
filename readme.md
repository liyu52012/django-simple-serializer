# Django Simple Serializer

---

Django Simple Serializer is a serializer to help user serialize django data or python list into json\xml\dict data in a simple way.

##Why Django Simple Serializer ?


###django.core.serializers
 This is a django built-in serializers, it serialzie querset but not a single model object. In addition, if you have DateTimeField into your model, the serializers will not work well(if you'd like using serialized data directly)
###QuerySet.values()
 As above, QuerySet.values() also not work well if you have DateTimeField into your model.
###django-rest-framework serializers
 django-rest-framework is a powerful tools to help you build REST API quickly. It has a powerful serializer but you have to use it with create the corresponding model serializer object first. 
###django simple serializer
For some people, we just want to get serialized data quickly and simply, so i make a simple way to get serialized data without extra opertion, this is why django simple serializer.

##Requirements

Django >= 1.4

##Installation

Install using pip:

    pip install django-simple-serializer

##Working with django simple serializer

#License

Copyright © Tom Christie.

All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this
list of conditions and the following disclaimer.
Redistributions in binary form must reproduce the above copyright notice, this
list of conditions and the following disclaimer in the documentation and/or
other materials provided with the distribution.
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.