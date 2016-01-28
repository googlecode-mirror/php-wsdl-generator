Serialization of complex structures is something I tried put didn't pursue further.
For the time being you can just return a string and decode it on the client side.

**Exceptions:** Exceptions are handled in `ServiceListPrinter->fault($ex)`. It is always the same type of exception returned: `SoapError`. The error message is automatically inserted in the WSDL.