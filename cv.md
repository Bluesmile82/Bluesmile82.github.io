---
layout: cv
title: "CV"
permalink: cv/
---
{% for post in site.tags.cv %}
  <div class="container">
      <div class="row">
          <div class="col-lg-8 col-lg-offset-2">
              <div class="modal-body">
                  <img src="../img/foto.jpg" class="img-responsive img-centered img-circle" style="width: 100px" alt="{{ post.alt }}">
                      {{ post.content }}
              </div>
          </div>
      </div>
  </div>
{% endfor %}