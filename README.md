<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vertical Tabs with Bootstrap</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
<div class="container my-5">
    <div class="row">
        <div class="col-md-3">
            <!-- Vertical Tabs -->
            <div class="nav flex-column nav-pills" id="v-pills-tab" role="tablist" aria-orientation="vertical">
                <button class="nav-link active" id="v-pills-tab1" data-bs-toggle="pill" data-bs-target="#tab1" type="button" role="tab" aria-controls="tab1" aria-selected="true">Tab 1</button>
                <button class="nav-link" id="v-pills-tab2" data-bs-toggle="pill" data-bs-target="#tab2" type="button" role="tab" aria-controls="tab2" aria-selected="false">Tab 2</button>
                <button class="nav-link" id="v-pills-tab3" data-bs-toggle="pill" data-bs-target="#tab3" type="button" role="tab" aria-controls="tab3" aria-selected="false">Tab 3</button>
            </div>
        </div>
        <div class="col-md-9">
            <!-- Tab Content -->
            <div class="tab-content" id="v-pills-tabContent">
                <!-- Tab 1 Details -->
                <div class="tab-pane fade show active" id="tab1" role="tabpanel" aria-labelledby="v-pills-tab1">
                    <ul class="nav nav-pills mb-3" id="pills-tab1-subtabs" role="tablist">
                        <li class="nav-item" role="presentation">
                            <button class="nav-link active" id="tab1-subtab1" data-bs-toggle="pill" data-bs-target="#tab1-detail1" type="button" role="tab" aria-controls="tab1-detail1" aria-selected="true">Detail 1</button>
                        </li>
                        <li class="nav-item" role="presentation">
                            <button class="nav-link" id="tab1-subtab2" data-bs-toggle="pill" data-bs-target="#tab1-detail2" type="button" role="tab" aria-controls="tab1-detail2" aria-selected="false">Detail 2</button>
                        </li>
                        <li class="nav-item" role="presentation">
                            <button class="nav-link" id="tab1-subtab3" data-bs-toggle="pill" data-bs-target="#tab1-detail3" type="button" role="tab" aria-controls="tab1-detail3" aria-selected="false">Detail 3</button>
                        </li>
                    </ul>
                    <div class="tab-content">
                        <div class="tab-pane fade show active" id="tab1-detail1" role="tabpanel" aria-labelledby="tab1-subtab1">
                            Content for Tab 1, Detail 1
                        </div>
                        <div class="tab-pane fade" id="tab1-detail2" role="tabpanel" aria-labelledby="tab1-subtab2">
                            Content for Tab 1, Detail 2
                        </div>
                        <div class="tab-pane fade" id="tab1-detail3" role="tabpanel" aria-labelledby="tab1-subtab3">
                            Content for Tab 1, Detail 3
                        </div>
                    </div>
                </div>

                <!-- Tab 2 Details -->
                <div class="tab-pane fade" id="tab2" role="tabpanel" aria-labelledby="v-pills-tab2">
                    <ul class="nav nav-pills mb-3" id="pills-tab2-subtabs" role="tablist">
                        <li class="nav-item" role="presentation">
                            <button class="nav-link active" id="tab2-subtab1" data-bs-toggle="pill" data-bs-target="#tab2-detail1" type="button" role="tab" aria-controls="tab2-detail1" aria-selected="true">Detail 1</button>
                        </li>
                        <li class="nav-item" role="presentation">
                            <button class="nav-link" id="tab2-subtab2" data-bs-toggle="pill" data-bs-target="#tab2-detail2" type="button" role="tab" aria-controls="tab2-detail2" aria-selected="false">Detail 2</button>
                        </li>
                        <li class="nav-item" role="presentation">
                            <button class="nav-link" id="tab2-subtab3" data-bs-toggle="pill" data-bs-target="#tab2-detail3" type="button" role="tab" aria-controls="tab2-detail3" aria-selected="false">Detail 3</button>
                        </li>
                    </ul>
                    <div class="tab-content">
                        <div class="tab-pane fade show active" id="tab2-detail1" role="tabpanel" aria-labelledby="tab2-subtab1">
                            Content for Tab 2, Detail 1
                        </div>
                        <div class="tab-pane fade" id="tab2-detail2" role="tabpanel" aria-labelledby="tab2-subtab2">
                            Content for Tab 2, Detail 2
                        </div>
                        <div class="tab-pane fade" id="tab2-detail3" role="tabpanel" aria-labelledby="tab2-subtab3">
                            Content for Tab 2, Detail 3
                        </div>
                    </div>
                </div>

                <!-- Tab 3 Details -->
                <div class="tab-pane fade" id="tab3" role="tabpanel" aria-labelledby="v-pills-tab3">
                    <ul class="nav nav-pills mb-3" id="pills-tab3-subtabs" role="tablist">
                        <li class="nav-item" role="presentation">
                            <button class="nav-link active" id="tab3-subtab1" data-bs-toggle="pill" data-bs-target="#tab3-detail1" type="button" role="tab" aria-controls="tab3-detail1" aria-selected="true">Detail 1</button>
                        </li>
                        <li class="nav-item" role="presentation">
                            <button class="nav-link" id="tab3-subtab2" data-bs-toggle="pill" data-bs-target="#tab3-detail2" type="button" role="tab" aria-controls="tab3-detail2" aria-selected="false">Detail 2</button>
                        </li>
                        <li class="nav-item" role="presentation">
                            <button class="nav-link" id="tab3-subtab3" data-bs-toggle="pill" data-bs-target="#tab3-detail3" type="button" role="tab" aria-controls="tab3-detail3" aria-selected="false">Detail 3</button>
                        </li>
                    </ul>
                    <div class="tab-content">
                        <div class="tab-pane fade show active" id="tab3-detail1" role="tabpanel" aria-labelledby="tab3-subtab1">
                            Content for Tab 3, Detail 1
                        </div>
                        <div class="tab-pane fade" id="tab3-detail2" role="tabpanel" aria-labelledby="tab3-subtab2">
                            Content for Tab 3, Detail 2
                        </div>
                        <div class="tab-pane fade" id="tab3-detail3" role="tabpanel" aria-labelledby="tab3-subtab3">
                            Content for Tab 3, Detail 3
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
