### everyday

<div class="row">

  <div class="col-md-6 col-lg-3 text-center mb-4">
    <div style="overflow: hidden; border-radius: 15px; box-shadow: 0 6px 12px rgba(0,0,0,0.15); transition: transform 0.3s ease; cursor: pointer;" onclick="try { $('#imageModal').modal('show'); document.getElementById('modalImage').src = '../../static/assets/img/moon.jpg'; document.getElementById('modalCaption').innerText = 'Moon'; } catch(e) { window.open('../../static/assets/img/moon.jpg', '_blank'); }">
      <img src="../../static/assets/img/moon.jpg" alt="Moon" style="width: 100%; height: 200px; object-fit: cover; border-radius: 15px 15px 0 0;">
    </div>
    <p style="font-style: italic; color: #555; margin-top: 10px;">Lovely night walk under bright moon</p>
  </div>

  <div class="col-md-6 col-lg-3 text-center mb-4">
    <div style="overflow: hidden; border-radius: 15px; box-shadow: 0 6px 12px rgba(0,0,0,0.15); transition: transform 0.3s ease; cursor: pointer;" onclick="try { $('#imageModal').modal('show'); document.getElementById('modalImage').src = '../../static/assets/img/run.jpg'; document.getElementById('modalCaption').innerText = 'Run'; } catch(e) { window.open('../../static/assets/img/run.jpg', '_blank'); }">
      <img src="../../static/assets/img/run.jpg" alt="Run" style="width: 100%; height: 200px; object-fit: cover; border-radius: 15px 15px 0 0;">
    </div>
    <p style="font-style: italic; color: #555; margin-top: 10px;">My first 10km running！</p>
  </div>

  <div class="col-md-6 col-lg-3 text-center mb-4">
    <div style="overflow: hidden; border-radius: 15px; box-shadow: 0 6px 12px rgba(0,0,0,0.15); transition: transform 0.3s ease; cursor: pointer;" onclick="try { $('#imageModal').modal('show'); document.getElementById('modalImage').src = '../../static/assets/img/climb.jpg'; document.getElementById('modalCaption').innerText = 'Climb'; } catch(e) { window.open('../../static/assets/img/climb.jpg', '_blank'); }">
      <img src="../../static/assets/img/climb.jpg" alt="Climb" style="width: 100%; height: 200px; object-fit: cover; border-radius: 15px 15px 0 0;">
    </div>
    <p style="font-style: italic; color: #555; margin-top: 10px;">First time ever as a climer!</p>
  </div>

  <div class="col-md-6 col-lg-3 text-center mb-4">
    <div style="overflow: hidden; border-radius: 15px; box-shadow: 0 6px 12px rgba(0,0,0,0.15); transition: transform 0.3s ease; cursor: pointer;" onclick="try { $('#imageModal').modal('show'); document.getElementById('modalImage').src = '../../static/assets/img/yes.jpg'; document.getElementById('modalCaption').innerText = 'Yes'; } catch(e) { window.open('../../static/assets/img/yes.jpg', '_blank'); }">
      <img src="../../static/assets/img/yes.jpg" alt="Yes" style="width: 100%; height: 200px; object-fit: cover; border-radius: 15px 15px 0 0;">
    </div>
    <p style="font-style: italic; color: #555; margin-top: 10px;">Hiking at Zhongnan Mountain all by myself</p>
  </div>
  
</div>

<!-- Modal -->
<div class="modal fade" id="imageModal" tabindex="-1" role="dialog" aria-labelledby="imageModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered modal-lg" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="modalCaption">Image</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body text-center">
        <img id="modalImage" src="" class="img-fluid" alt="">
      </div>
    </div>
  </div>
</div>