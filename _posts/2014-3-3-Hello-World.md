---
layout: post
title: You're up and running!
---

Next you can update your site name, avatar and other options using the _config.yml file in the root of your repository (shown below).

![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.

```java
private void createPolygon(){
        ArrayList<LatLng> list = new ArrayList<LatLng>();
        PolygonOptions polygonOptions = null;
        try {
            for (int i=0; i<listOfDistricts.size(); i++) {
                list = readItems(listOfDistricts.get(i));
                Polygon polygon = m_map.addPolygon(new PolygonOptions().addAll(list)
                        .strokeColor(Color.TRANSPARENT)
                        .fillColor(listOfColors.get(i)));

                mapOfPolygons.put(arrayOfDistricts[i], polygon);

            }

            Log.i("list2", list.toString());
        } catch (JSONException e) {
            e.printStackTrace();
        }


    }```
