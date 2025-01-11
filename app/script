 <script>
        let currentUser = null;
        const API_URL = 'https://r0c8kgwocscg8gsokogwwsw4.zetaverse.one/db';
        const AUTH_TOKEN = 'P0I1xbGg0DhvL0IBDzqLtvyZUh53';

        // Utility Functions
        function showLoading() {
            document.getElementById('loadingOverlay').classList.remove('hidden');
        }

        function hideLoading() {
            document.getElementById('loadingOverlay').classList.add('hidden');
        }

        function showPage(pageId) {
            ['loginPage', 'signupPage', 'dashboard'].forEach(id => {
                document.getElementById(id).classList.add('hidden');
            });
            document.getElementById(pageId).classList.remove('hidden');
        }

        function showLogin() {
            showPage('loginPage');
        }

        function showSignup() {
            showPage('signupPage');
        }

        function showDashboard() {
            showPage('dashboard');
            loadStores();
        }
