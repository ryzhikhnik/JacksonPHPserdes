# PHP serialize and deserialize to java object via jackson

Usage:
ObjectMapper om = new ObjectMapper(new PHPJsonFactory());

    om.writeValueAsString(Object object) - serialize java object to json php format

    ow.readValue(String phpStr, class<T>) - deserialize php json string to java object


