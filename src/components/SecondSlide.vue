<template>
    <v-row class="d-flex align-center justify-center my-md-10">
        <v-col cols="auto" class="">
            <h1>Our Core Features</h1>
            <p class="mt-md-2 mb-md-3">Dive into the innovative features that make SecureAudit Pro the go-to for
                businesses seeking bulletproof cyber security.</p>
            <div class="w-100 d-flex justify-space-between gc-5 mt-md-8">
                <div class="feature-block  pa-md-4 d-flex flex-column align-center">
                    <v-icon color="#cdcdcd" size="40" icon="mdi-fire" />
                    <h1>24/7 Monitoring</h1>
                    <p>Benefit from around-the-clock surveillance of your digital assets, ensuring that threats are
                        spotted and stopped anytime, day or night.</p>
                </div>
                <div class="feature-block  pa-md-4 d-flex flex-column align-center">
                    <v-icon color="#cdcdcd" size="40" icon="mdi-clock-outline" />
                    <h1>Risk Assessment</h1>
                    <p>Pinpoint potential vulnerabilities with our strategic risk assessments, designed to forecast and
                        neutralize threats effectively.
                    </p>
                </div>
                <div class="feature-block pa-md-4 d-flex flex-column align-center">
                    <v-icon color="#cdcdcd" size="40" icon="mdi-cloud-outline" />
                    <h1>Compliance Checks
                    </h1>
                    <p>Stay ahead of regulations with ongoing compliance checks that cover local, national, and
                        international cybersecurity standards.
                    </p>
                </div>
            </div>
        </v-col>
    </v-row>
</template>

<script lang="ts" setup>
//
</script>

<style scoped lang="scss">
h1 {
    font-size: 40px;
    font-weight: 700;
}

p {
    font-size: 20px;
    line-height: 24px;
}

.feature-block {
    width: 100%;
    background-color: #000000;
    border-radius: 16px;
    color: #ffffff;
    max-width: 300px;

    h1 {
        font-size: 16px;
        font-weight: 500;
        margin-top: 10px;
    }

    p {
        font-size: 14px;
        margin-top: 5px;
        color: #cdcdcd;
    }
}
</style>