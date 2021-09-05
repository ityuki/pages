# いつきの物置

<script>
$.md.stage("all_ready").subscribe(function(done){
    var obj;
    obj = $("#md-main-navbar ul.nav.navbar-nav:has(li) li.dropdown:eq(1) a");
    if (obj.length > 0){
        obj[0].href = "https://github.com/ityuki/pages/blob/master/" + $.md.mainHref;
        obj[0].target = "_blank";
    }
    obj = $("#md-main-navbar ul.nav.navbar-nav:has(li) li.dropdown:eq(2) a");
    if (obj.length > 0){
        obj[0].href = "https://github.com/ityuki/pages/edit/master/" + $.md.mainHref;
        obj[0].target = "_blank";
    }
    done();
}
);
</script>


[オプション]()

  * [原文](https://github.com/ityuki/pages)
  * [編集](https://github.com/ityuki/pages)
