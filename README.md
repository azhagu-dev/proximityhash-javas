ProximityHash: Geohashes in Proximity
Geohash is a geocoding system invented by Gustavo Niemeyer and placed into the public domain. It is a hierarchical spatial data structure which subdivides space into buckets of grid shape, which is one of the many applications of what is known as a Z-order curve, and generally space-filling curves.
Example program


 public static void main(String[] args) {
        double latitude=	24.189992;
        double longitude=55.762293;
        double radius=5000;
        int precision=6;
        System.out.println(createGeohash(latitude, longitude, radius, precision, false, 1, 12));
    }
